# README
# A1: Data Curation
### data-512-a1
### Autumn 2021

The goal of this assignment is to construct, analyze, and publish a dataset of monthly traffic
on English Wikipedia from January 1 2008 through August 30 2021.

Data about Wikipedia page traffic is pulled from two different Wikimedia REST API endpoints and combined into a single dataset. Some simple data processing steps are performed on the data before the visualization is generated.

Source data licenses: 

CC-BY-SA 3.0 https://creativecommons.org/licenses/by-sa/3.0/
GFDL licenses https://www.gnu.org/copyleft/fdl.html

Wikimedia Foundation REST API terms of use: https://www.mediawiki.org/wiki/REST_API#Terms_and_conditions

Legacy PageCount documentation 
https://wikitech.wikimedia.org/wiki/Analytics/AQS/Legacy_Pagecounts
https://wikimedia.org/api/rest_v1/#/Pagecounts_data_(legacy)/get_metrics_legacy_pagecounts_aggregate_project_access_site_granularity_start_end

PageView API documentation
https://wikitech.wikimedia.org/wiki/Analytics/AQS/Pageviews
https://wikimedia.org/api/rest_v1/#/Pageviews_data/get_metrics_pageviews_aggregate_project_access_agent_granularity_start_end

Important notes:
Data from the Pageview API excludes spiders/crawlers, while data from the Pagecounts API
does not.

Final data file includes the following fields:

- year (YYYY)
- month (MM)
- pagecount_all_views (num_views)
- pagecount_desktop_views (num_views)
- pagecount_mobile_views (num_views)
- pageview_all_views (num_views)
- pageview_desktop_views (num_views)
- pageview_mobile_views (num_views)
