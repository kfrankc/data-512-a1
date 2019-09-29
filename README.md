# data-512-a1
A1 Assignment for University of Washington's DATA 512 course

### Goal of Project

In this project, I constructed, analyzed, and published a dataset of monthly traffic on the English Wikipedia from January 1, 2008, until August 30, 2019. I followed the best practices of documenting my process via my Jupyter notebook and this README so that my results are reproducible. All of my code and documentation are published in this Github repository. 

### License of Data

The terms of use for this data can be found [here](https://foundation.wikimedia.org/wiki/Terms_of_Use/en)

Link to the [Wikimedia Foundation REST API terms of use](https://www.mediawiki.org/wiki/REST_API#Terms_and_conditions)

### Links to Relevant API Docs

* [Legacy Pagecount API](https://wikitech.wikimedia.org/wiki/Analytics/AQS/Legacy_Pagecounts)
* [Pageview API](https://wikitech.wikimedia.org/wiki/Analytics/AQS/Pageviews)

### Final File Values

The final CSV file, `en-wikipedia_traffic_200712-201809`, has the following schema:

| `year` | `month` | `pagecount_desktop_views` | `pagecount_mobile_views` | `pagecount_all_views` | `pageview_desktop_views` | `pageview_mobile_views` | `pageview_all_views` |
|---------|--------|---------|--------|--------|--------|--------|--------|

There are 8 columns, and 141 rows.

### Known Issues

* The data from the Pageview API excludes spiders/crawlers
* The data from Pagecount API does not

