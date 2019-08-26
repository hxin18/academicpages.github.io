---
layout: archive
title: "Selected Projects"
permalink: /Projects/
author_profile: true
---
Weenix Operating System
============
Implemented kernel processes & thread, virtual file system, virtual memory of an operating system including but not limited to mutex lock, context switch and wait, path resolution, address spaces. Passed over 1000 tests on
both kernel-level and user-level thread.
[code](https://github.com/hxin18/402kernel)

Distributed Lookup System
============
In this project, my contribution is consist of two parts
* Implemented a distributed lookup system from scratch. It contains three backend databases, an intermediate
server, a client and a monitor and established stream sockets to transmit queries and results among all devices.
* Implemented the methods of exact matching, prefix matching and suffix matching for backend server.
[code](https://github.com/hxin18/distributed-lookup)


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
More details can be seen [here](https://hxin18.github.io/files/reportem.pdf)

Link Prediction using Textual and Graphical Features
============
In this project,we mainly focus on link prediction on the scholarly data. The dataset contains citation networks of 27770 documents with the information of title, abstract, authors and publish time. It is the same data using in [AXA Data Science Winter School : Tsinghua, Renmin and Ecole Polytechnique](https://www.kaggle.com/c/link-prediction-tu)

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
I get the f1 score of 0.9765

More details can be seen [here](https://hxin18.github.io/files/report.pdf)
