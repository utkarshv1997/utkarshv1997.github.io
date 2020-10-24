---
title: ""
excerpt: ""
author_profile: true
permalink: /projects/
redirect_from:
  - /project/

---
# Application Monitoring using libc Call Interception, AppDynamics, Cisco R&D

* Developed an easy to use, language-agnostic, platform-agnostic monitoring tool, for distributed applications, in Golang. The same approach could be used to develop
a data-monitoring system over the bytes flowing over sockets of a distributed application.  
* Research work accepted for publication in the [**Springer ICICCS 2020** journal](https://www.springer.com/in/book/9789811584428). (To be published by the end of 2020) <br>

> **Citation** : Harish Thuwal, **Utkarsh Vashishtha** <br>
> **Abstract** : Generally Available Application Monitoring solutions comprise basic aggregated metrics. This paper collects such metrics in the form of raw data. 
> We have worked out a very primitive piece written in Golang, which manifests results from HTTP/HTTPS calls from/to the system being monitored. 
> This process can be easily extended and applied to various architectures that use the libc library to make low-level system calls to interact 
> with sockets or in a more basic sense, files. The experimentation and the proof of concept was carried out on various languages viz C, Java, Python, 
> and Golang itself using docker and some classic open-source compilers.

# Prediction of Earthquakes using Nowcasting

Guide: [Prof. Navneet Goyal](https://universe.bits-pilani.ac.in/pilani/goel/profile)

* Developed a ML model for Earthquake prediction near water bodies using Dynamics Factor models and Kalman Filters.
* The implementation was based out of data provided by the Ministry of Earth Sciences, Government of India based on the 
paper [Geodetic Constraints on Tectonic and Anthropogenic Deformation and Seismogenesis of Koyna–Warna Region, India](https://pubs.geoscienceworld.org/ssa/bssa/article-abstract/108/5B/2933/548495/Geodetic-Constraints-on-Tectonic-and-Anthropogenic?redirectedFrom=fulltext)

# Human Fall Detection

Guide: [Dr. Sanjay Singh](https://www.ceeri.res.in/profiles/sanjay-singh/)

* Developed a deep learning model for detecting a human fall using temporal and spatial aggregations from video processing.
* Employed the 3D-CNN and LSTM models for mapping features to a data point which was then fed to a Softmax classifier.

# Heart disease detection using Active Learning

Guide: [Prof. Navneet Goyal](https://universe.bits-pilani.ac.in/pilani/goel/profile)

* Used pool-based sampling, where large number of unlabelled data is gathered at once and has a small amount of labelled data, for choosing 
Queries to ask an expert for labelling. 
* This was achieved by using the Query-by-committee (QBC) algorithm, with Kullback-Leibler divergence, over an ensemble of SVM, Random Forest and Quadratic Discriminant Analysis.

# Hybrid Music Recommender System

Guide: [Prof. Poonam Goyal](https://www.bits-pilani.ac.in/Pilani/poonam/profile)

* Created a Hybrid Music recommender system with collaborative filtering using the [Million Song dataset](http://millionsongdataset.com/) 
and content-based filtering using the [Free Music Archive Audio data](https://github.com/mdeff/fma) 
* A song recommendation was made using Sentiment Analysis of recent tweets created by the user.

# Comprehensive stock analysis & Beta and Stock price analysis :

Guide: [Prof. Rajan Pandey](https://www.bits-pilani.ac.in/pilani/rajanpandey/profile)

* Fundamental analysis and time-series technical analysis of *Punjab National Bank* in the National Stock Exchange. 
* Used data from the [NSE Website](https://www.nseindia.com/), [Moneycontrol.com](www.moneycontrol.com), and Capitaline Database for beta and stock price
analysis of [Akzo Nobel India Ltd.](https://akzonobel.co.in/)
