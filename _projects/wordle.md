---
layout: page
title: Wordle Analytics - Decoding the Daily Challenge
description: A wordle analytics dashboard and the process of creating an end-to-end data analytics project at zero cost.
img: assets/img/wordle1.png
github: https://github.com/sahilvora10/WordleAnalyticsDashboard
importance: 1
arrow_icon: true
category: kaggle datasets
---
<div class="container mt-4 pl-0">
  <div class="text-left">
  <span class="mr-2">Created Using:</span>
    <span class="badge" style="background-color: var(--global-theme-color); border-color: var(--global-theme-color) !important">Python</span>
    <span class="badge" style="background-color: var(--global-theme-color); border-color: var(--global-theme-color) !important">Tweepy</span>
    <span class="badge" style="background-color: var(--global-theme-color); border-color: var(--global-theme-color) !important">BeautifulSoup</span>
    <span class="badge" style="background-color: var(--global-theme-color); border-color: var(--global-theme-color) !important">Kaggle</span>
    <span class="badge" style="background-color: var(--global-theme-color); border-color: var(--global-theme-color) !important">SendGrid</span>
    <span class="badge" style="background-color: var(--global-theme-color); border-color: var(--global-theme-color) !important">Heroku</span>
    <span class="badge" style="background-color: var(--global-theme-color); border-color: var(--global-theme-color) !important">Google Looker Studio</span>
  </div>
</div>
<p></p>

Embark on a journey through data and analytics with me, where I explore the fascinating world of web scraping, analytics dashboards, and live website integration, all at zero cost. This adventure began with a simple yet wildly popular word game that took the internet by storm during the pandemic - Wordle.



<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/wordle.png" title="wordle" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<p><strong>Links to all the resources</strong></p>
<ul>
  <li><i class="fab fa-github"></i> <a href="https://github.com/sahilvora10/WordleAnalyticsDashboard">GitHub Repo</a></li>
  <li><i class="fab fa-kaggle"></i> <a href="https://www.kaggle.com/vora1011/wordletweets">Wordle - Kaggle Dataset</a></li>
  <li><i class="fab fa-medium"></i> <a href="https://medium.com/@vorasahil01/how-well-are-you-doing-in-wordle-a2f6b0d096c3">Medium Article: A step by step working of this dashboard.</a></li>
  <li><i class="fas fa-chart-line"></i> <a href="https://sahilvora10.github.io/WordleProject/">Live Dashboard.</a></li>
</ul>

<i>If you have any questions or inquiries, please feel free to contact me at <a href="mailto:sahilvora2021@gmail.com">sahilvora2021@gmail.com</a></i>

<p><strong>So, what's Wordle?</strong></p> It's a daily word game that challenges players to guess a five-letter word within six attempts. Each guess is met with colored tiles offering feedback on letter matches and their correct positions. What sets Wordle apart is its accessibility; it's not an app, requires no logins, and can be played just once a day. After each game, players can share their color-coded tile grids, withholding the day's answer. You can stil play it <a href = "https://www.nytimes.com/games/wordle/index.html">here</a>

This is how the tweets used to look like and the only data that was available publically during that time
{% twitter https://twitter.com/MKBHD/status/1491065937017163779?s=20 %}

<p><strong>Unveiling the Dashboard</strong></p>

As tweets flooded in from Wordle enthusiasts, I saw an opportunity to gain insights into everyone's Wordle attempts. Which attempt led to success for most players? This curiosity ignited my journey into creating my very first analytics dashboard.

<p><strong>The Dashboard's Insights</strong></p>

So, what does this dashboard reveal? It provides a daily snapshot of how Wordle enthusiasts worldwide tackled the game the previous day. Each day, the dashboard updates with data scraped from Twitter, collecting a sample dataset of 20,000 tweets. It showcases the distribution of players attempting the game in Hard Mode, where revealed hints must be used in the next guess. This data corresponds to the previous Wordle ID, focusing on the day's gameplay. The dashboard also offers a cumulative overview of the past seven days and highlights players who cracked the Wordle on their first attempt. Furthermore, it tracks the preference for Hard Mode over the past week.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/wordle_dashboard.gif" title="wordle dashboard" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Preview of the live dashboard
</div>

<p><strong> How was the Dashboard created? </strong></p>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Wordl.png" title="Architecture" zoomable=true class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Architecture Flow created for the dashboard to run at zero-cost. <a href="https://medium.com/@vorasahil01/how-well-are-you-doing-in-wordle-a2f6b0d096c3">For more details.</a>
</div>

<p><strong>A Journey of Firsts</strong></p>

This journey wasn't just about creating a dashboard; it opened doors to several first-time experiences. I obtained my first <a href="https://www.kaggle.com/vora1011/wordletweets">Kaggle dataset</a>, authored my maiden <a href="https://medium.com/@vorasahil01/how-well-are-you-doing-in-wordle-a2f6b0d096c3">Medium article</a> that has step-by-step procedure on how this dashboard was created, and crafted a <a href="https://sahilvora10.github.io/WordleProject/">live dashboard</a> viewed by many. It even indirectly influenced the game's creators to release a leaderboard-like statistics feature shortly after I launched my project.
