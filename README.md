## "Big Data for Internet application" Course at Politecnico di Torino

This course tackles the issues that come up in the Big Data era. It delves into the processing of large datasets and extracting valuable information from them. The focus is on learning how to collect, store, retrieve, and analyze big data for useful insights in Internet applications. The course doesn't just cover data analytics; it also explores new ways of programming, like MapReduce and Spark RDD-based programs. It discusses how these methods can help engineers extract knowledge from data. The class includes hands-on examples of applying big data techniques for data science in the internet domain.

### Here, a short description of each lab is provided:

In the "Introduction to Spark" lab, we learn how to run a simple Spark program using the Big Data cluster of Politecnico.

The objective of the "Spark RDD" lab is to start playing around with Apache Spark and processing large text files. We had a large text file with the frequencies of words in food reviews in Amazon, in the format word\tfreq, where freq is an integer.

In "Spark SQL & RDD" lab, we will analyze historical data about the usage of the bike sharing system of Barcelona. The occupancy of the stations where users can pick up or drop off
bikes is considered. The main task consists in identifying the most "critical" timeslots (day of the week, hour) for each station. The analysis is based on 2 files available in the HFDS shared folder of the BigData@Polito cluster:
The first file contains the historical information about the number of used and free slots for ~3000 stations from May 2008 to September 2008. Each line of register.csv
corresponds to one reading about the situation of one station at a specific timestamp. Each line has the following format (\t stands for the tab character) :
#### station\ttimestamp\tused_slots\tfree_slots
The second one contains the description of the stations. Each line of registers.csv has the following format:
#### id\tlongitude\tlatitude\tname
