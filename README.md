# Multi-Threaded_WebCrawler
This is a 'crawler' to 'crawl' (visit, fetch contents of) a list of URLs, starting with an empty queue and a seed website, then recursively shrink/grow it (remove items, possibly add new items), till the queue is empty again.

# Results

fetch_NewsSite.csv - Contains the URLs it attempts to fetch, a two column spreadsheet, column 1 containing the URL and 
column 2 containing the HTTP/HTTPS status code received (where the name “NewsSite” is replaced by the news website name in the table above that we 
are crawling). The number of rows is pre-set to a limit of no more than 20,000. 

visit_NewsSite.csv - the files it successfully downloads, a four column spreadsheet, column 1 containing the 
URLs successfully downloaded, column 2 containing the size of the downloaded file (in 
Bytes), column 3 containing the no of outlinks found, and column 4 containing the resulting content-type.
fetch_NewsSite.csv 
