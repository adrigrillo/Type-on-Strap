---
layout: post
title: NYCSparkTaxi
feature-img: "assets/img/portfolio/nyc-taxi.jpg"
img: "assets/img/portfolio/nyc-taxi-thumb.png"
date: 20 July 2017
tags: [big data, New York, apache spark, taxi, routes, profit, python]
---

# Spark based big data architecture to analyse New York city taxi trips

This is my final bachelor's degree project, it takes as starting point the challenge
gave during the 2015 DEBS Grand Challenge. It uses all the traces of the trips made
during 2013 by the New York City taxis, which were more than 170 million of trips, and
it does some queries in them, measuring the efficiency of the systems 
used. There will be two queries, one that search the top ten frequent routes and the top
ten profitable areas for the taxi driver, both of them taking in consideration a time 
window to do it.

This architecture is based and developed in Apache Spark in all of its implementations 
and the distributed file system of Apache Hadoop in some. Apache Parquet is 
used for the files to save the processed data as a file type.

The documentation of this final degree project could be found in docs folder in 
a compilable Latex format. The full repo can be found here: 
https://github.com/adrigrillo/NYCSparkTaxi

Image courtesy of [prayitnophotography](https://www.flickr.com/photos/prayitnophotography/)