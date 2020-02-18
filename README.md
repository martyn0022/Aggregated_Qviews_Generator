## Wikidumps_pageview_aggregator
App that generates a list of Q numbers with its aggregated pageviews (across languages) into a .txt document which could be used to extract page views for whatever entity the user queries

## Instructions

1. Go to this [Dropbox link](https://www.dropbox.com/s/9d6cbvhdvpmov4o/AggregatedQviews.txt?dl=0) and download the AggregatedPageview.txt file to query for wikipedia page views on 2019-12 be sure to add this file into the same folder directory

2. Open a Git Bash terminal in the folder directory and input the following :
```shell
python GenerateQviews.py
```
3. Specify if you want to use a location ID or bbox coordinates to determine the area you want to query on OpenStreetMap as prompted on the console.

4. Specify the OpenStreetMap Key-Value pair (ie. historic-castle) as prompted by the console

5. Hit enter. The following sorted list of Qnumber-Views should be saved into a file named ```Qviews.txt```.
