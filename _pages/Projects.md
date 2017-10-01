---
layout: archive
title: "Selected Projects"
permalink: /Projects/
author_profile: true
---
Smart Home System using Rasperry Pi
============
In this project, we design prototype of a smart home system based on Raspburry Pi. 
* We make full use of sensors to measure multiple environmental parameters 
* Based on these parameters we can turn on or turn off the electrical devices like light or alarming system automatically. 
* we combine the data-mining techniques into the prediction part of our system, making our system more intelligent.
<table>
          	<tbody>
          		<tr>
          			<td>
                  <img src="/images/em1.png" style="display:block; margin-left:15px; width:80%">
          			</td>
          			<td style="width:340px">
          			<img src="/images/em2.png" style="display:block; margin-left:15px; width:80%">
          			</td>
          		</tr>
          	</tbody>
          </table>

Link Prediction using Textual and Graphical Features
============
In this project,we mainly focus on link prediction on the scholarly data. The dataset contains citation networks of 27770 documents with the information of title, abstract, authors and publish time. It is the same data using in [Prof. Xinbing Wang](http://iwct.sjtu.edu.cn/Personal/xwang8/index.html)

In this data challenge, I utilized 19 features and build a boosting system to predict the citing probability. The 19 features are:
* Topic representation selected by PLSA
* Lsa representation of abstract
* Lsa representation of topic
* Tf-idf representation of abstract
* Tf-idf representation of title
* Tw-idf representation of title
* Tw-idf representation of abstract
* Number of common words in abstract
* Number of common words in title
* Community of papers
* Pagerank score of cited paper
* Pagerank score of citing paper
* Clustering score of cited paper
* Clustering score of citing paper
* Degree of cited paper
* Degree of citing paper
* Number of common author
* Time gap
I get the $f_1$ score of 0.9765
