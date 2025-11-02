---
layout: page
title: Covid-19 Vaccine Stance Detection and Social Media Exploration
description: Exploring Diverse Opinions on Covid-19 Vaccines through Social Media Tweets.
img: assets/img/proj2.png
github: https://github.com/sahilvora10/Covid-19-VaccineAnalysis
importance: 2
category: academics
arrow_icon: true
giscus_comments: true
---
<div class="container mt-4 pl-0">
  <div class="text-left">
  <span class="mr-2">Created Using:</span>
    <span class="badge" style="background-color: var(--global-theme-color); border-color: var(--global-theme-color) !important">Python</span>
    <!-- Add more skills or tools as needed -->
  </div>
</div>
<p></p>
In the ever-evolving landscape of social media, every issue, even a pandemic and its vaccine, has its champions and critics. This project delves deep into the nuances of public sentiment surrounding the COVID-19 vaccine. By analyzing tweets from both Pro-Vaccine and Anti-Vaccine campaigns, we uncover intriguing insights about cluster formations, campaign connectivity, and the epicenters of these discussions.


<i>The code for this project is available at <a href="https://github.com/sahilvora10/Covid-19-VaccineAnalysis">sahilvora10/Covid-19-VaccineAnalysis</a>. If you have any questions or inquiries, please feel free to contact me at <a href="mailto:sahilvora2024@gmail.com">sahilvora2024@gmail.com</a></i>

<p><strong>Project Objective</strong></p>
Gather and analyze Twitter data focused on the COVID-19 Vaccine to gain valuable insights and conduct in-depth exploratory analysis.



<p><strong>How Data Was Scraped</strong></p>
<p>Twitter data was collected using Twitter's APIs, which require the creation of a developer account and a request for elevated access. In this project, we utilized Twitter's version 2 APIs. With the help of the Tweepy library, data was obtained by searching for specific hashtags. Below is a step-by-step explanation of the data scraping process:</p>
<ol>
  <li><strong>Utilizing Tweepy Cursor Methods:</strong>
    <ul>
      <li>Tweepy provides cursor methods that allow us to retrieve data in bulk.</li>
      <li>The API called the <code>search_tweets</code> method, searching for tweets containing the specified hashtags.</li>
      <li>For the smaller dataset, approximately 30 tweets per hashtag were fetched, while 100 tweets were collected for the larger dataset.</li>
      <li>The following tweet attributes were collected: <code>created_at</code>, <code>id</code>, <code>in_reply_to_screen_name</code>, <code>in_reply_to_status_id</code>, <code>in_reply_to_user_id</code>, <code>retweeted_id</code>, <code>retweeted_screen_name</code>, <code>user_mentions_screen_name</code>, <code>user_mentions_id</code>, <code>full_text</code>, <code>user_id</code>, <code>screen_name</code>, and <code>followers_count</code>.</li>
    </ul>
  </li>
  <li><strong>Defining a Date Range:</strong>
    <ul>
      <li>To narrow down the search, a date range starting from April 1, 2021, was chosen. This timeframe coincided with the global introduction of COVID-19 vaccines.</li>
    </ul>
  </li>
  <li><strong>Managing Rate Limits:</strong>
    <ul>
      <li>Due to rate limits imposed by Twitter's developer portal, we could make up to 180 requests every 15 minutes.</li>
      <li>Each response typically contained 10 to a maximum of 100 results.</li>
      <li>When the maximum limit was reached, the crawler script paused for 15 minutes before resuming data retrieval.</li>
    </ul>
  </li>
  <li><strong>Selecting Relevant Hashtags:</strong>
    <ul>
      <li>Keywords for both anti-vaccine and pro-vaccine campaigns, such as #StopVaccination and pro-vaccine hashtags, were chosen based on a repository.</li>
      <li>During a dry run, some hashtags did not yield the desired number of tweets and were consequently excluded.</li>
      <li>The selected hashtags are stored in <code>AntiVaccineKeywords.txt</code> and <code>ProVaccineKeywords.txt</code> and can be updated as needed.</li>
    </ul>
  </li>
</ol>

<p><strong>Results</strong></p>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/AntiVaccineDiffusionNetworkGraph.png" title="anti_vaccine" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/ProVaccineDiffusionNetworkGraph.png" title="pro_vaccine" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Diffusion Network created for Anti-Vaccine(left) and Pro-Vaccine(right) attitudes.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/AntiVaccineDiffusionNetworkLargestConnectedGraph.png" title="anti_vaccine" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/ProVaccineDiffusionNetworkLargestConnectedGraph.png" title="pro_vaccine" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Diffusion Network for the largest connected subgraph created for Anti-Vaccine(left) and Pro-Vaccine(right) attitudes.
</div>

<p>Based on the analysis of the graphs and network structures, notable differences emerge between the two campaign tweets:</p>

<ul>
  <li><strong>Anti-Vaccine Campaign:</strong>
    <ul>
      <li>The diffusion network for the Anti-Vaccine campaign exhibits a dense interconnectedness.</li>
      <li>Certain tweets clearly serve as central hubs or origin points within this network.</li>
      <li>Many tweets emanate from these central points, contributing to the overall density.</li>
      <li>Additionally, there are smaller, connected components within this network.</li>
    </ul>
  </li>
  <li><strong>Pro-Vaccine Campaign:</strong>
    <ul>
      <li>In contrast, the diffusion network for the Pro-Vaccine campaign is distinct.</li>
      <li>It features a single, less densely populated central point or origin.</li>
      <li>The interconnectedness among tweets in this network is less pronounced.</li>
    </ul>
  </li>
</ul>

<p>This analysis underscores the differing patterns of information diffusion and connectivity between the Anti-Vaccine and Pro-Vaccine campaigns.</p>

<p><strong>Summary</strong></p>
<p>The project provides insights into the creation of social networks using Twitter data, revealing patterns of closed connections and network formations among campaigns with shared objectives. The analysis of Anti-Vaccine campaign tweets highlights a strong and densely connected opinion network.</p>

