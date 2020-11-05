---
layout: post
title: MetroMiner
img: "assets/img/portfolio/subway.png"
color: rgb(229,60,53)
date: 29 May 2018
tags: [nlp, python, kafka, streaming]
---

Python application that continuously analyzes tweets about underground system of Madrid city (Metro Madrid) in order to detect faults and disruptions in the service. 

The architecture is based in micro-services connected between each other using Apache Kafka. 
The tweets are gathered using the [Twitter real-time streaming API](https://developer.twitter.com/en/docs/tweets/filter-realtime/overview) and analysed using [Spacy](https://spacy.io/).

The code can be found here: <https://github.com/adrigrillo/metro-miner>