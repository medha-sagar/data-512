
# DATA 512 - Human Centered Data Science
## Assignment 1 : Data Curation
### Introduction

The goal of this assignment is to construct, analyze, and publish a dataset of monthly traffic on English Wikipedia from January 1 2008 through August 30 2020. All analysis should be performed in a single Jupyter notebook and all data, documentation, and code should be published in a single GitHub repository.

The purpose of the assignment is to start to familiarize you with the Jupyter Notebook environment and with some best practices for open scientific research in designing and implementing your project, and make your project fully reproducible by others: from data collection to data analysis.

### Data

- The Legacy Pagecounts API (documentation (https://wikitech.wikimedia.org/wiki/Analytics/AQS/Legacy_Pagecounts) , endpoint (https://wikimedia.org/api/rest_v1/#!/Pagecounts_data_(legacy)/get_metrics_legacy_pagecounts_aggregate_project_access_site_granularity_start_end) ) provides access to desktop and mobile traffic data from December 2007 through July 2016.

- The Pageviews API (documentation (https://wikitech.wikimedia.org/wiki/Analytics/AQS/Pageviews), endpoint (https://wikimedia.org/api/rest_v1/#!/Pageviews_data/get_metrics_pageviews_aggregate_project_access_agent_granularity_start_end)) provides access to desktop, mobile web, and mobile app traffic data from July 2015 through last month.

Terms of use: https://www.mediawiki.org/wiki/REST_API#Terms_and_conditions

### Packages

- numpy : (https://numpy.org/)
- pandas : (https://pandas.pydata.org/)
- matplotlib : (https://matplotlib.org/)
- requests : (https://requests.readthedocs.io/en/master/)

### Files

- EN_WIKI_VIEWS.png : Final visualization file
- en-wikipedia_traffic_200712-202008.csv: Consolidated data for all pageviews from legacy system (including spiders and crawlers)
- pagecounts_desktop-site_200801-202008.json: Pageviews data from legacy system from desktop channel (including spiders and crawlers)
- pagecounts_mobile-site_200801-202008.json: Pageviews data from legacy system from mobile channel (including spiders and crawlers)
- pageviews_desktop_200801-202008.json: Pageviews data from new system from desktop channel 
- pageviews_mobile-app_200801-202008.json: Pageviews data from new system from mobile app channel 
- pageviews_mobile-web_200801-202008.json: ageviews data from new system from mobile web channel 

### Installation

Data Dictionary for en-wikipedia_traffic_200712-202008.csv:

| Column | Description |
| ------ | ------ |
| year | Year |
| month | Month |
| pagecount_all_views | Total views from legacy system |
| pagecount_desktop_views | Total views from legacy system (desktop) |
| pagecount_mobile_views | Total views from legacy system (mobile) |
| pageview_all_views | Total views from new system  |
| pageview_desktop_views | Total views from new system (desktop) |
| pageview_mobile_views | Total views from new system (mobile) |


### Visualization

![image](EN_WIKI_VIEWS.png)

#### License

 [MIT LICENSE](https://opensource.org/licenses/MIT)
