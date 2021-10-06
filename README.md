# data-512-a1
# A1: Data Curation
## Autumn 2021

The goal of this assignment is to construct, analyze, and publish a dataset of monthly traffic
on English Wikipedia from January 1 2008 through August 30 2021.

Data about Wikipedia page traffic is pulled from two different Wikimedia REST API endpoints and combined into a single dataset. Some simple data processing steps are performed on the data before the visualization is generated.

Source data license: 

Wikimedia Foundation REST API terms of use: https://www.mediawiki.org/wiki/REST_API#Terms_and_conditions

Legacy PageCount documentation 
https://wikitech.wikimedia.org/wiki/Analytics/AQS/Legacy_Pagecounts
https://wikimedia.org/api/rest_v1/#/Pagecounts_data_(legacy)/get_metrics_legacy_pagecounts_aggregate_project_access_site_granularity_start_end

PageView API documentation
https://wikitech.wikimedia.org/wiki/Analytics/AQS/Pageviews
https://wikimedia.org/api/rest_v1/#/Pageviews_data/get_metrics_pageviews_aggregate_project_access_agent_granularity_start_end


Describe the values of all fields in your final data file.



List any known issues or special considerations with the data that would be useful
for another researcher to know. For example, you should describe that data from
the Pageview API excludes spiders/crawlers, while data from the Pagecounts API
does not.
