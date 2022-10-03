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

**Final Output Files**

    step2_part1.png
    
    Time series for the articles that have the highest average page requests and the lowest average page requests for desktop access and mobile access.
    
    step2_part2.png
    
    Time series for the top 10 article pages by largest (peak) page views over the entire time by access type. You first find the month for each article that contains the highest (peak) page views, and then order the articles by these peak values.
    
    step2_part3.png
    
    Time series of pages that have the fewest months of available data.
