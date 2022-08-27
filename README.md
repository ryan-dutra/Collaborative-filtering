# Recommender-System

This repo are an attempt to implementing and *improving* the *Bourhim et al. (2018)*'s graph-based collaborative filtering approach for recommendation systems (GBCF-RS) $^{[1]}$.

Additionally, it also aims to delves deeper into some specific steps of the proposed pipeline to investigating how algorithmic variations can impact the recommender overall performance -- similarlly to what was done in *Bouhim et al. (2019)* $^{[2]}$. However, a biggest range of algorithmic variations is going to be implemented compared with the cited work.
Finally, experiment on new open datasets will be executed to compare the efficiency and performance in various scenarios of data volume.


***Bouhrim's work proposal:*** 

The Bouhrim's approach for improving the accuracy of hybrid approaches takes into account the following assumptions: 
* (1) A user-base is a network of highly similar sub-communities. Any inference should be made on these communities’ level rather than on the whole user-base; and
* (2) Some users are more embedded in this Homophilous communities than others. Inferring recommendations from keynodes rather than similar users can lead to more accurate results.

***Incorporated concepts:***

* (1) User-based collaborative filtering;
* (2) Community detection;
* (3) Key nodes identification. ;

***Steps needed for implementing Bouhrim's GBCF:***

*   **Step 1:** Create a Homophily network based on similarity measures (using the jaccard similarity index);
*   **Step 2:** Identify the communities in the Homophily network (using the Louvain algorithm);
*   **Step 3:** Identify the key nodes per community (using centrality measures);
*   **Step 4:** Profile the key node per community;
*   **Step 5:** Computing recommendations for community users.





<font size="2">**[1]** BOURHIM, Sofia; BENHIBA, Lamia; IDRISSI, MA Janati. **Towards a Novel Graph-based collaborative filtering approach for recommendation systems**. In: Proceedings of the 12th International Conference on Intelligent Systems: Theories and Applications. 2018. p. 1-6. Available in  https://dl.acm.org/doi/abs/10.1145/3289402.3289524</font> 

<font size="2">**[2]** BOURHIM, Sofia; BENHIBA, Lamia; IDRISSI, MA Janati. Investigating algorithmic variations of an RS Graph-based collaborative filtering approach. In: Proceedings of the ArabWIC 6th Annual International Conference Research Track. 2019. p. 1-6. Available in  https://dl.acm.org/doi/abs/10.1145/3333165.3333177</font> 
