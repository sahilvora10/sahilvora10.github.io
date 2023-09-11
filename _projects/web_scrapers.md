---
layout: page
title: Web Scraping Tools- A Comprehensive Survey
description: Exploring and evaluating web scraping tools for efficient data extraction from various online sources
img: assets/img/ui_us_news.png
github: https://github.com/sahilvora10/Survey-for-Web-Scrapers
arrow_icon: true
importance: 3
category: academics
---
<div class="container mt-4 pl-0">
  <div class="text-left">
  <span class="mr-2">Created Using:</span>
    <span class="badge" style="background-color: var(--global-theme-color); border-color: var(--global-theme-color) !important">Python</span>
    <span class="badge" style="background-color: var(--global-theme-color); border-color: var(--global-theme-color) !important">Google Looker Studio</span>
    <span class="badge" style="background-color: var(--global-theme-color); border-color: var(--global-theme-color) !important">Tweepy</span>
    <span class="badge" style="background-color: var(--global-theme-color); border-color: var(--global-theme-color) !important">Scrapy</span>
    <span class="badge" style="background-color: var(--global-theme-color); border-color: var(--global-theme-color) !important">Octoparse</span>
    <span class="badge" style="background-color: var(--global-theme-color); border-color: var(--global-theme-color) !important">Selenium</span>
    <span class="badge" style="background-color: var(--global-theme-color); border-color: var(--global-theme-color) !important">BeautifulSoup</span>
    <span class="badge" style="background-color: var(--global-theme-color); border-color: var(--global-theme-color) !important">Reaper</span>
    <!-- Add more skills or tools as needed -->
  </div>
</div>
<p></p>
In today's data-driven landscape, web scraping is essential for extracting valuable insights from online sources. This project was created as part of an exploration survey to evaluate various web scraping tools and their performance with different types of data. This process, involving software tools to gather data from websites, empowers organizations, researchers, and individuals for purposes like market research and content aggregation. The rising popularity of tools like BeautifulSoup, Scrapy, and Octoparse has made data extraction accessible and cost-effective.

<i>The code for this project is available at <a href="https://github.com/sahilvora10/Survey-for-Web-Scrapers">sahilvora10/Survey-for-Web-Scrapers</a>. If you have any questions or inquiries, please feel free to contact me at <a href="mailto:svora7@asu.edu">svora7@asu.edu</a></i>

<p><strong>Project Objective</strong></p>
 Evaluate and analyze diverse web scraping tools to streamline data collection from news, social media, and e-commerce websites. The assessment will consider factors like speed, accuracy, usability, and cost-effectiveness, providing valuable insights into choosing the most suitable tool for specific business requirements.

 <p><strong>Dataset Overview</strong></p>
 For this project we collected following data from different sources.
 <ul>
  <li>Amazon: Product data collected for search results for the term "iPhone"</li>
  <li>US News: Data collected for best engineering universities in USA</li>
  <li>Youtube: Video data collected for video search results for the term "Data Science"</li>
  <li>Twitter: Tweets collected for hashtags #ChatGPT</li>
</ul>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/scrapy_data.png" title="dataset overview" zoomable=true class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    For this project, these were the data that was collected using various tools.
</div>
 
<p><strong>Metrics for Evaluation</strong></p>
For this project we evaluated and formulated some metrics that would be helpful for the evaluation.
<ul>
  <li>Performance Efficiency
    <ul>
      <li>Time taken to scrape the same set of data</li>
      <li>Max Limit</li>
      <li>Fault Tolerance</li>
    </ul>
  </li>
  <li>Ease of Use
    <ul>
      <li>Proper Documentation for libraries and tools</li>
      <li>Scraping procedure</li>
    </ul>
  </li>
  <li>API vs Non-API
    <ul>
      <li>Amount of Coding needed</li>
      <li>Availability of Non-API tools</li>
    </ul>
  </li>
  <li>Cost to Scrape Data
    <ul>
      <li>Is the tool free to use</li>
      <li>Charges involved per API call</li>
      <li>Upper limit on the amount of data</li>
    </ul>
  </li>
</ul>

<p><strong>Results and Finding</strong></p>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/amazon.png" title="amazon" zoomable=true class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/usnews.png" title="usnews" zoomable=true class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/youtube.png" title="youtube" zoomable=true class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/twitter.png" title="twitter" zoomable=true class="img-fluid rounded z-depth-1" %}
    </div>
    
</div>
<div class="caption">
    Evaluation Results for Amazon, US News, Youtube and Twitter. (in order)
</div>

<p><strong>Visualizations</strong></p>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/ui_us_news.png" title="dataset overview" zoomable=true class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    With the amount of data we collected, we also created a live interactive dashboard using Google Looker Studio <i><a href="https://sahilvora10.github.io/Survey-for-Web-Scrapers/">(available here)</a></i> that helps is visualizing the data.
</div>

<p><strong>Summary</strong></p>
<p>Our study of web scraping technology shows its efficiency and flexibility, allowing automated data collection. While each tool has unique limitations, data from sites like Twitter, Youtube, US News, and Amazon offer valuable insights. Our detailed tool evaluation sets our project apart, empowering users with valuable insights into web scraping.</p>
