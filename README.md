# Pennsylvania state parks exploration with FourSquare Place API 

The state of Pennsylvania has a total of 121 state parks, as of 2016. 

The short project here intended to first cluster in an unsupervised way, then to fit for parks' popularity to identify main factors impacting park quality (which may be used for recommendation as well as recognizing potential issues may be improved for the park).
Things learnt from the PA parks may be generalized to other states and the framework can be expanded by incorporating information from other place APIs. 

Use [nbviewer](https://nbviewer.jupyter.org/github/qcabel/PA-state-parks/blob/main/state_park_PA_foursquare.ipynb) to view the maps. 

The popularity of the park (# of users liked the park in FourSquare) and total number of nearby venues (& how they would distribute among the main categories) influence how these parks would be clustered. 

* Super popular state park, <em>e.g.</em>, Point State Park located in the city of Pittsburgh
<img src=img/point_state.png width="220">

* State park located in the rural areas/state forests (red circles), where true outdoor experiences are expected

* In rural areas but highly attractive
<img src=img/kinzua.png width="320">

* Popular state park with good outdoor service as well as lots of restaurants nearby
<img src=img/neshaminy.png width="220">

* State park near township with amper food and shop services (although not as popular as the above cluster)
<img src=img/archbald.png width="250">

* State park near river/creek with water activity service, <em>e.g.</em>, the state park near Lake Erie
<img src=img/erie.png width="220">

