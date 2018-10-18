## Data-512-a1

This goal of this repo is to provides a notebook environment to measure Wikipedia traffic from 2007-2018 using two different API endpoints, the Legacy Pagecounts API and the Pageviews API.

## Data sources

Two major data sources are used for this repo with established API endpoints:

[The Legacy Pagecounts API](https://wikitech.wikimedia.org/wiki/Analytics/AQS/Legacy_Pagecounts#Pagecounts):provides access to desktop and mobile traffic data from December 2007 through July 2016.

[The Pageviews API](https://wikitech.wikimedia.org/wiki/Analytics/AQS/Pageviews#Monthly_counts):provides access to desktop, mobile web, and mobile app traffic data from July 2015 through last month.
 
 ## Repo structure and Data dictionary
 
 ### Structure
![struct](https://i.imgur.com/8UkOw61.png)
 
 ### Data Dictionary

| Column  | Description |
| ------------- | ------------- |
| year  | Year of data  |
| month  | Month of Data  |
| pagecount_all_views  | Total (Mobile +  Desktop) views on Wiki based on pagecount API   |
| pagecount_desktop_views  | Total Desktop views on Wiki based on pagecount API  |
| pagecount_mobile_views  | Total Mobile views on Wiki based on pagecount API  |
| pageview_all_views  | Total (Mobile +  Desktop) views on Wiki based on pageviews API   |
| pageview_desktop_views  | Total Desktop views on Wiki based on pageviews API  |
| pageview_mobile_views  | Total Mobile  views on Wiki based on pageviews API  |

# Visualization
![viz](https://github.com/pshivraj/data-512-a1/blob/notebook_initial/wiki_2007-2018_views.png)

# Special consideration with Data

Page Count API returns values which include bots (spiders/crawlers), whereas the Page Views API does not, thus this could lead to conflicting results.

## License
 
 Primary License for this repo:
 
 [WIKIMEDIA](https://foundation.wikimedia.org/wiki/Terms_of_Use/en)
 
 [MIT](https://opensource.org/licenses/MIT)
