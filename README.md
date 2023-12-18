Data Set Description

In 2011, URL shortening service Bitly *Bitly.com* partnered with the US goverment website *USA.gov* to provide a feed of anonymous data gathered from users who shorten links ending with *.gov* or *.mil*.  This service is shut down at 2017. 

In this database, each line contains a common form of web data known as **JSON**, which stands for *JavaScript Object Notation* . Python has both built-in and 3rd party libraries for converting a JSON string into a Python dictionary object. Then we can use *pd.DataFrame* convert dictionary object into Dataframe for our analysis.

each line has a number of identifying attributes.

In [18]: records[0] <br>
Out[18]: <br>
{'a': 'Mozilla/5.0 (Windows NT 6.1; WOW64) AppleWebKit/535.11 (KHTML, like Gecko)
Chrome/17.0.963.78 Safari/535.11', <br>
 'al': 'en-US,en;q=0.8', <br>
 'c': 'US',<br>
 'cy': 'Danvers',<br>
 'g': 'A6qOVH',<br>
 'gr': 'MA',<br>
 'h': 'wfLQtf',<br>
 'hc': 1331822918,<br>
 'hh': '1.usa.gov',<br>
 'l': 'orofrog',<br>
 'll': [42.576698, -70.954903],<br>
 'nk': 1,<br>
 'r': 'http://www.facebook.com/l/7AQEFzjSi/1.usa.gov/wfLQtf',<br>
 't': 1331923247,<br>
 'tz': 'America/New_York',<br>
 'u': 'http://www.ncbi.nlm.nih.gov/pubmed/22415991'}<br>
 
