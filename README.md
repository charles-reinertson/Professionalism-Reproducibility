# Professionalism-Reproducibility
The goal of this project is to construct, analyze, and publish a dataset of monthly article traffic for a select set of pages from English Wikipedia from January 1, 2015 through September 30, 2022. The main parts of this project are data acquisition and analysis.

Wikimedia Foundation REST API terms of use: https://www.mediawiki.org/wiki/REST_API#Terms_and_conditions

Wikipedia - The Pageviews API ([documentation](https://wikitech.wikimedia.org/wiki/Analytics/AQS/Pageviews), [endpoint](https://wikimedia.org/api/rest_v1/#!/Pageviews_data/get_metrics_pageviews_aggregate_project_access_agent_granularity_start_end)) licensed under the CC-BY-SA 3.0 and GFDL licenses

**Intermediary Data Files**

    dino_monthly_mobile_<start201501>-<end202210>.json

      Description: JSON file with keys as dinosaurs article titles and value is a list containing a time-series of article traffic

    dino_monthly_desktop_<start201501>-<end202210>.json

      Description: JSON file with keys as dinosaurs article titles and value is a list containing a time-series of article traffic

    dino_monthly_cumulative_<start201501>-<end202210>.json

      Description: JSON file with keys as dinosaurs article titles and value is a list containing a time-series of article traffic
