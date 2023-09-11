---
layout: page
title: Indian Premiere League Data Collection
description: Curated collection of datasets on the IPL for in-depth analysis of one of cricket's most popular tournaments.
img: assets/img/ipl.png
importance: 2
arrow_icon: true
kaggle: https://www.kaggle.com/datasets/vora1011/ipl-2008-to-2021-all-match-dataset
category: kaggle datasets
---
<div class="container mt-4 pl-0">
  <div class="text-left">
  <span class="mr-2">Created Using:</span>
    <span class="badge" style="background-color: var(--global-theme-color); border-color: var(--global-theme-color) !important">Python</span>
    <span class="badge" style="background-color: var(--global-theme-color); border-color: var(--global-theme-color) !important">Selenium</span>
    <span class="badge" style="background-color: var(--global-theme-color); border-color: var(--global-theme-color) !important">BeautifulSoup</span>
    <!-- Add more skills or tools as needed -->
  </div>
</div>
<p></p>
Many of us have watched the movie Moneyball. The film summarizes that with proper scouting and believing in the statistics of players, a great team can be built. However, this analysis can be done with an excellent dataset to help analyze the players, strengths, and weaknesses.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/ipl.png" title="ipl" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<a href="https://www.iplt20.com/">Indian Premiere League</a> is among the most famous cricket league with players coming from worldwide. What makes this series more competitive this year is the auction resulting in all players changing their squad and two new teams added to the league. With IPL starting every year and as a true Cricket fan, I belived there was a need for datasets showing match information and also data for each delivery. So I created few datasets by scraping data from multiple sources to create the following datasets. Here is an overview of the datasets that I created in 2022 published on Kaggle.

<p></p>
<div class="table-responsive">
  <table class="table table-bordered">
    <thead>
      <tr>
        <th style="border-top: initial;">Kaggle Dataset</th>
        <th style="border-top: initial;">Description</th>
        <th style="border-top: initial;">Upvotes</th>
        <th style="border-top: initial;">Views</th>
        <th style="border-top: initial;">Downloads</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>
          <a href="https://www.kaggle.com/datasets/vora1011/ipl-2008-to-2021-all-match-dataset" target="_blank">
            IPL 2008 to 2022 All Match Dataset
          </a>
        </td>
        <td>
          IPL 2008-2022 Ball By Ball and Match Info Data
        </td>
        <td>
          <i class="fas fa-medal" style="color: #c0c0c0;"></i> 97
        </td>
        <td>42k</td>
        <td>10k</td>
      </tr>
      <tr>
        <td>
          <a href="https://www.kaggle.com/datasets/vora1011/ipl-2022-match-dataset" target="_blank">
            IPL 2022 Match Dataset
          </a>
        </td>
        <td>
          IPL 2022 Ball By Ball and Match Info Data
        </td>
        <td>
          <i class="fas fa-medal" style="color: #8E5B3D;"></i> 91
        </td>
        <td>38k</td>
        <td>8k</td>
      </tr>
      <tr>
        <td>
          <a href="https://www.kaggle.com/datasets/vora1011/ipl-2022-player-statistics" target="_blank">
             IPL 2022 Player Statistics
          </a>
        </td>
        <td>
          A data for all players playing Tata IPL 2022 with all time IPL and T20 stats
        </td>
        <td>
          <i class="fas fa-medal" style="color: #8E5B3D;"></i> 43
        </td>
        <td>16k</td>
        <td>3k</td>
      </tr>
    </tbody>
  </table>
</div>

<p></p>

<i>The code for this project is available at <a href="https://github.com/sahilvora10/IPL_Data_Extraction">sahilvora10/IPL_Data_Extraction</a>. If you have any questions or inquiries, please feel free to contact me at <a href="mailto:sahilvora2021@gmail.com">sahilvora2021@gmail.com</a></i>

<p><strong><a href="https://www.kaggle.com/datasets/vora1011/ipl-2008-to-2021-all-match-dataset" target="_blank">
            IPL 2008 to 2022 All Match Dataset
          </a></strong></p>

This dataset is the widely used dataset that combines all the available data for each of the match played from the intial opening season of 2008 till 2022. It also has statistics and data about each ball that has ever been delivered within these years.

<ul>
  <li>The dataset was among the most used dataset under Sport Category for 2022</li>
  <li>The data was scraped from <a href="https://cricsheet.org/" target="_blank">Cricsheet</a>.</li>
  <li>Around 226k rows of data was fetched.</li>
  <li>Around 37 different available features for the dataset.</li>
</ul>

<p><strong><a href="https://www.kaggle.com/datasets/vora1011/ipl-2022-match-dataset" target="_blank">
            IPL 2022 Match Dataset
          </a></strong></p>

This dataset was a daily updated open-sourced data while the tournament was active. It also has statistics and data about each ball that has ever been delivered within these years.

<ul>
  <li>The dataset was used by many contributors to predict the best players while the tournament was live!</li>
  <li>The data was scraped from <a href="https://cricsheet.org/" target="_blank">Cricsheet</a>.</li>
  <li>Around 17.9k rows of data was fetched.</li>
  <li>Around 37 different available features for the dataset.</li>
</ul>

<p><strong><a href="https://www.kaggle.com/datasets/vora1011/ipl-2022-player-statistics" target="_blank">
             IPL 2022 Player Statistics
          </a></strong></p>

With the new season of IPL with the squad finalized, this dataset was a concise dataset to get statistics of all the players for the year 2022. This data can be used to analyze to make your dream team, which can also help anyone play fanatasy leagues and tournaments.

This dataset has a CSV file with all players in the list. It contains details of each player's all-time batting, bowling, and fielding figures in IPL and T20 stats, either international or domestic, apart from IPL.

<ul>
  <li>The dataset was among the most used dataset under daily category in 2022.</li>
  <li>The data was scraped from <a href="https://sports.ndtv.com/ipl-2022/auction/teamsquad" target="_blank">NDTV Sports</a>.</li>
  <li>Contains data for all the 237 players that played in IPL 2022</li>
  <li>Around 80 different available features for the dataset.</li>
</ul>
