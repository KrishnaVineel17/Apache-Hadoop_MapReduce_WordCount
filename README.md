# Apache-Hadoop_MapReduce_WordCount
Brief Introduction:
**Apache Hadoop** is an open source software framework for storage and large scale processing of data-sets on clusters of commodity hardware. Hadoop is an Apache top-level project being built and used by a global community of contributors and users.Hadoop was created by Doug Cutting and Mike Cafarella in 2005. It was originally developed to support distribution for the Nutch search engine project. Doug, who was working at Yahoo! at the time and is now Chief Architect of Cloudera, named the project after his son's toy elephant. Cutting's son was 2 years old at the time and just beginning to talk. He called his beloved stuffed yellow elephant **"Hadoop"**.

**MapReduce** is a programming paradigm that enables massive scalability across hundreds or thousands of servers in a Hadoop cluster. As the processing component, MapReduce is the heart of Apache Hadoop. The term "MapReduce" refers to two separate and distinct tasks that Hadoop programs perform. The first is the map job, which takes a set of data and converts it into another set of data, where individual elements are broken down into tuples **(key/value pairs)**.

The reduce job takes the output from a map as input and combines those data tuples into a smaller set of tuples. As the sequence of the name MapReduce implies, the reduce job is always performed after the map job.

MapReduce programming offers several benefits to help you gain valuable insights from your big data:
    1.**Scalability**. Businesses can process petabytes of data stored in the Hadoop Distributed File System (HDFS).
    2.**Flexibility**. Hadoop enables easier access to multiple sources of data and multiple types of data.
    3.**Speed**. With parallel processing and minimal data movement, Hadoop offers fast processing of massive amounts of data.
    4.**Simple**. Developers can write code in a choice of languages, including Java, C++ and Python.
    
Main Objective:
This assignment focuses on how to use Apache Hadoop MapReduce on Word Count Application. Here we give a .txt file as an input to the mapreduce program and get the output of **&lt;key, value>** pairs of frequencies for each word preset in the text file. 
