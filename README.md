# data-512-a1
Human Centered Data Science
The goal of this analysis was to create a monthly traffic on english wikipedia across devices and report the trends. 

Data set used is from Wikipedia
The link to the API which was used to pull the data: https://www.mediawiki.org/wiki/REST_API#Terms_and_conditions
Data was accessed through two API's 
1. The Legacy Pagecounts API. Documentation: https://wikitech.wikimedia.org/wiki/Analytics/AQS/Legacy_Pagecounts
2. PageViews API. Documentation: https://wikitech.wikimedia.org/wiki/Analytics/AQS/Pageviews

Theis folder contains the source files in 5 different JSON files with the naming convension of apiname_accesstype_firstmonth_lastmonth.
The JSON files contain aggreggated monthly pageview data by accesstype. The data from the pageviews API excludes bot as it was filtered only for user generated request. While in the pagecount legacy data bots are included in the data.

en-wikipedia_traffic_200712-201909.csv is the processed version of the file. This has column names as below (this has been definted in the wiki here (https://wiki.communitydata.science/Human_Centered_Data_Science_(Fall_2019)/Assignments#A1:_Data_curation)

Data has been combined together into a single file from multiple files offline in excel, the juypter notebook contains all the information till creating the multiple individual files. 

This folder also contains an excel sheet which was used to generate the visualization. I converted the visits into Million and graphed them. The excel with the visualization is en-wikipedia_traffic_200712-201909.xls.



