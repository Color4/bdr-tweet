<h3><b> On Identifying Disaster-Related Tweets: Matching-based or Learning-based? </b></h3>

<br>
Introduction 
<hr>
Social media feeds such as tweets are emerging as platforms contributing to situational awareness during disasters. Information shared on Twitter by both affected population (e.g., requestingassistance,warning)andthoseoutsidetheimpactzone (e.g., providing assistance) would help ﬁrst responders, decision makers and the public to understand the situation ﬁrst-hand. Timely analysis of disaster-relevant tweets requires an ability to automatically ﬁnd tweets related to a particular disaster. This problem is challenging as tweet messages are often short and unstructured, and learning-based approach for ﬁltering disasterrelated tweets may not provide satisfactory results. Thus, we propose a simple yet effective matching-based algorithm for ﬁltering relevant messages. To evaluate the two approaches, we putthemintoaframeworkproposedforanalyzingdiaster-related posts. Analysis results on ten datasets with various disaster types show the pros and cons of each approach. 
<br>
<br>

Regarding the Dataset
<hr>
Disasters folder contains geo tagged tweets for 15 disasters accross USA.
<br>
1. California Fire <br>
2. Iowa Storm, Tornadoes and Flood <br>
3. Iowa Storm, Tornadoes and Flood 2 <br>
4. Iowa Storm <br>
5. Jersey Storm <br>
6. Michigan Storm <br>
7. Napa Earthquake <br>
8. Newyork Storm <br>
9. Oklahoma Storm <br>
10. Texas Storm <br>
11. Vermont Storm <br>
12. Virginia Storm <br>
13. Washington Mudslide <br>
14. Washington Storm <br>
15. Washington Wildfire <br>


References:

Disasters in 2015 + 1016
https://www.fema.gov/disasters/grid/year/2016?field_disaster_type_term_tid_1=All

Informative/Noninformative Dataset
https://github.com/sajao/CrisisLex/tree/master/data/CrisisLexT26

Library
SVM classifier: https://github.com/daoudclarke/pysvmlight/tree/master/lib
