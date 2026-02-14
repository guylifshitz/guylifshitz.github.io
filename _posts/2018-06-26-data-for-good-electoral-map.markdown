---
layout: post
title:  "Data for Good: Open Electoral Map"
date:   2018-06-26 22:34:29 +0300
categories: 
    - projects
    - political science
---
A web interface displaying a map of France divided in "X" circonscriptions, with a slider to change their number. Circonscriptions must be equal in population compact (no weird shapes) and continuous (not broken into multiple non-touching parts). As much as possible they must not go outside of municipal and departmental limits. We developed an evolutionnary k-means clustering algorithm to create equally sized population clusters. 

The institutional reform project discussed in the French National Assembly aimed to reduce the number of deputies from 577 to 404, with 69 of them elected through proportional representation. To implement this, the government intended to redraw the electoral map, decreasing the number of constituencies to 335 based primarily on demographic criteria. The question of how this map should be redrawn raises many questions of demographic and territorial equality and representation. This redistricting plan risked undermining the constitutional principle of equal representation. Maintaining at least one deputy per department—even those with small populations—created significant disparities. 

To address these issues, working within a season of "Data for Good Paris", our project "Redécoupage citoyen" proposed ignoring departmental boundaries in the redistricting process. We developed a model that defined constituencies of equal population size, regardless of traditional geographic limits. Our solution relied on objective, non-partisan algorithms and demographic data. The project was carried out collaboratively by researchers, developers, legal experts, and elected officials, and the results were made [publicly accessible](https://404.codefor.fr/){:target="_blank"}. Our work demonstrated that it was possible to create balanced constituencies without compromising local identity or practical governance.

[Project website](https://404.codefor.fr/){:target="_blank"}

![picture 1]({{"assets/images/2018-06-26-data-for-good-electoral-map/recoupage-title.png",  | relative_url }})

![picture 1]({{"assets/images/2018-06-26-data-for-good-electoral-map/circonscriptions_et_departements-3.png",  | relative_url }})

![picture 1]({{"assets/images/2018-06-26-data-for-good-electoral-map/france.png",  | relative_url }})

![picture 1]({{"assets/images/2018-06-26-data-for-good-electoral-map/grands_electeurs_sous100k.png",  | relative_url }})

