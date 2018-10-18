## Data-512-a1

This goal of this repo is to provides a notebook environment to measure Wikipedia traffic from 2007-2018 using two different API endpoints, the Legacy Pagecounts API and the Pageviews API.

## Data sources

Two major data sources are used for this repo with established API endpoints:

[The Legacy Pagecounts API](https://wikitech.wikimedia.org/wiki/Analytics/AQS/Legacy_Pagecounts#Pagecounts):provides access to desktop and mobile traffic data from December 2007 through July 2016.

[The Pageviews API](https://wikitech.wikimedia.org/wiki/Analytics/AQS/Pageviews#Monthly_counts):provides access to desktop, mobile web, and mobile app traffic data from July 2015 through last month.

## License
 
 Primary License for this repo:
 
 [WIKIMEDIA](https://foundation.wikimedia.org/wiki/Terms_of_Use/en)
 
 [MIT](https://opensource.org/licenses/MIT)
 
 ## Repo structure and Data dictionary
 
 ### Structure
 ```
├── Data_curation.ipynb
├── README.md
├── data
│   ├── en-wikipedia_traffic_200801-201709.csv
│   ├── pagecounts_desktop-site_2007120100_2016080100.json
│   ├── pagecounts_mobile-site_2007120100_2016080100.json
│   ├── pageviews_desktop_2015070100_2018100100.json
│   ├── pageviews_mobile-app_2015070100_2018100100.json
│   └── pageviews_mobile-web_2015070100_2018100100.json
└── wiki_2007-2018_views.png

1 directory, 9 files
```
 
 ### Data Dictioanry

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
