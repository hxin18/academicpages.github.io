---
layout: archive
title: "Research"
permalink: /Research/
author_profile: true
---
My current research is mainly focused on information diffusion in social network. 
Previously I worked on developing topic-based methods for academic search and recommendation and visualzation of topic evolution, which are the theoretical part of our [Academic Search Engine](http://acemap.sjtu.edu.cn).

I am also interested in other machine learning related topics (eg. deep learning), data mining, espically graph mining and text mining. 


Topic Evolution in Scholarly Big-data
============
I worked to construct a probablistic graphical model to capture the temporal evolution of topics in scientific publications.

We have made such contributions:
* We provide a topic modelling based model to capture the timestamps and contents of topics.
* We visualised the evolution map of topic with gephi
* Our model can also be applied to information retrival of academic papers.

An Interactive Topic Model for academic recommendation
============
I worked to construct a topic-based model to recommend scientific publications.
We have made such contributions:
* We provide an interactive topic model with tree-structured priors and encode user feedback into the prior tree.
* We significantly increase the computational efficiency by adopting similar mechanism like SparseLDA. 
* We propose a crowdsourcing framework for recommending publications and further modify our interactive topic model     to a collaborative version. In this scenario, users with similar interests can fix a shared prior tree, which promotes article recommendation in related topics.
<div class="resume-item">
    <h3 class="resume-item-title">An Interactive Topic Model for academic recommendation</h3>
    <table>
    <tbody>
    <tr>
        <td><p>I worked to construct a topic-based model to recommend scientific publications.</p>
	<p>The objectives of this system are mainly:</p>
          <ul class="resume-item-list">
            <li>We provide an interactive topic model with tree-structured priors and encode user feedback into the prior tree.</li>
            <li>We significantly increase the computational efficiency by adopting similar mechanism like SparseLDA. </li>
            <li>We propose a crowdsourcing framework for recommending publications and further modify our interactive topic model to a collaborative version. In this scenario, users with similar interests can fix a shared prior tree, which promotes article recommendation in related topics.</li>
          </ul>
       	</td>
        <td style="width:340px">
        	<img src="/images/itm1.png" style="display:block; margin-left:15px; width:340px">
        </td>
         </tr>
  </tbody>
  </table>
  <tr><img src="/images/itm2.png" style="display:block; margin-left:15px; width:340px"></tr>
</div>
