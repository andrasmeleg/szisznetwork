# szisznetwork
This repository is to summarise my work for the assignment of the Network Science Course in Szisz

The goal of research is to set up a network of professional cyclist based on race participation data, and use tools learned on the network science course to do some analysis on this network. The work has 4 stages before handing in the assignment: 
1) Scraping data 
2) Formatting data sufficiently to be a good network (nodes are the riders, and links weighted between riders based on how much did 2 riders race on the same races)
3) Do network analysis
4) A theory discussion which should be at least 15000 characters. 

# Scraping data
To scrape data, I initially used arjunsudhir's work: https://github.com/arjunsudhir/procyclingstats/blob/master/procyclingstats_scraping_parsing.ipynb
Due to the fact that my python skills are probably not that good as his, after a while I started to found the code too complicated for my needs, so I had to improvise with my own methods during the scraping period. 
According to arjunsudhir, I collect the starters of prestigous races (Tour de France, etc.) and check how many unique riders participated in the scraped races. 
Afterwards, I do scrape all the html files of these riders, as one html file for each season the riders has participated, according to their procyclingstats page. 
I iterate over all the html files that I have downloaded, and collect the races each rider has participated during his carreer. 
I save to different rows each race participation for a rider, and put these to a pandas dataframe. 
I export the dataframe to a csv. 

# Setting up the network

# Network analysis

# Discussion of results
