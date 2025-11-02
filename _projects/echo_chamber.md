---
layout: page
title: Echo Chamber detection in Social Media
description: Unraveling the World of Social Media Echo Chambers, Their Influence on Information Consumption, and Advanced Detection Techniques on Twitter.
img: assets/img/largest.png
importance: 1
category: academics
arrow_icon: true
related_publications:
---
<div class="container mt-4 pl-0">
  <div class="text-left">
  <span class="mr-2">Created Using:</span>
    <span class="badge" style="background-color: var(--global-theme-color); border-color: var(--global-theme-color) !important">Python</span>
    <span class="badge" style="background-color: var(--global-theme-color); border-color: var(--global-theme-color) !important">Pytorch</span>
    <span class="badge" style="background-color: var(--global-theme-color); border-color: var(--global-theme-color) !important">Gephi</span>
    <span class="badge" style="background-color: var(--global-theme-color); border-color: var(--global-theme-color) !important">HuggingFace</span>
    <!-- Add more skills or tools as needed -->
  </div>
</div>
<p></p>
In today's world, the ubiquity of social media platforms like Twitter, Instagram, and Facebook has granted individuals unprecedented access to a wealth of information and connections. While this is empowering, it also presents two key challenges. Firstly, users grapple with information overload, making it difficult to discern what truly matters amidst the constant stream of content. Secondly, the issue of information disorder arises, as users encounter non-genuine information with specific agendas. Furthermore, social media tends to reinforce existing beliefs by exposing users to content aligned with their interests. This phenomenon creates echo chambers, where users are perpetually immersed in ideas identical to their own, fostering an environment where their thoughts echo and resonate.

This project was created to investigate the concept of echo chambers on Twitter, particularly in the context of political agendas like MAGA (MakeAmericaGreatAgain). We aimed to understand how social media platforms contribute to the formation of echo chambers by analyzing tweets from approximately 10,000 users. By classifying their political orientations as either Democratic or Republican, we identified and studied the corresponding echo chambers. Explore the impact of these digital environments and gain insights into the challenges of information overload and misinformation in today's social media landscape, as observed in this completed project.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/model.png" title="pipeline" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The Model Pipeline used for this project
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/twitter_scraping_architecture.png" title="Architecture" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Twitter Scraping and Similarity Measurement Architecture
</div>

<h4>Results</h4>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/weighted_largest.png" title="Network" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Weighted Based Echo Chambers for #MAGA
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/echo_chamber_with_twitter_users.png" zoomable=true title="Result" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Results and Evaluations using important Media and Political Users
</div>

<i>As this project involves sensitive data and is currently not open-sourced, we are unable to provide direct access to the code. If you have any questions or would like to learn more about the project and its details, please feel free to contact me at <a href="mailto:sahilvora2024@gmail.com">sahilvora2024@gmail.com</a>.</i>
