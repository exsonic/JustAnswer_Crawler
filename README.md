Web Crawler for Justanswer.com (Python Scrapy)
----------------------------------------------

bobi.pu@usc.edu


HOW TO USE:
-----------

1.Install Scrapy.(see its official website)

2.Command line: `Scrapy crawl JALinks -o links.json -t json`. To get all the disccusion links for "Cellphons" subject.

3.Command line: `Scrapy crawl JAThreads -o threads.json -t json`. To get all the discussion contents according to links.json and dumped them into threads.json file.

4.Command line: `Scrapy crawl JAExperts -o experts.json -t json`. To get all the experts' info in "Cellphones" field.

NOTE:
-----

1.To change the subject of discussions, like "MacComputer" instead of "Cellphones". Please edit the "linkSpiderStartURL.txt" file.

2.Before execute each command line, please make sure you've removed all the content of its output JSON file. 
