# Research Practicum 2019 – Research Plan 

> * Group Name: We Belong in a Museum
> * Group participants names: Cornell, Lincoln; Necaise, Aaron; Robkin, Jessica
> * Project Title: Towards a Model for Predicting Overland Trafficking Routes

## 1. Topic/Purpose Statement

This study addresses the viability of using computer simulations to identify the relationship between transportation networks and the smuggling of illicit antiquities. The purpose of this research is to provide a tool for law enforcement agencies and cultural heritage workers to recover looted archaeological artifacts before they reach the black market for sale. The first phase of this qualitative study will involve the running of weighted transportation simulations, guided by graph theory, to determine probable routes between selected archaeological sites that are known to have been looted during the 2014 ISIS insurgency in Syria and Iraq and known locations where caches of illicit artifacts have been recovered. The data from these simulations will be used to create a forced-decision survey designed to explore the routes that participants will select when informed of socio-political elements and available transportation networks.

## 2. General Introduction

Throughout the Middle East and North Africa (MENA) region, organized criminal gangs have taken advantage of political instability to loot archaeological sites for the purpose of selling illicit antiquities to fund political insurgency and terrorist organizations (Terrill, 2007). While looting in these areas is a centuries-old practice (Luke & Kersel, 2005), advances in technology and a growing demand for antiquities from this region has caused a dramatic increase in these activites (Terrill, 2007).  

<img src="images/DestructionofPalmyra2016_ArbreshInfo.jpg" width="400" > <img src="images/ISISPropoganda_DestructionofNimrud_BBCNews.jpg" width="450" >

During the insurgency of Syria and Iraq by ISIS in 2014, the terrorist organization often televised the systematic destruction of what they termed “idolatrous” heritage. Using this as justification for the destruction of cultural heritage sites in the region, ISIS quietly looted these sites prior to their televised destruction, with the funds gained on the black market used to further support their effort (Terrill 2017). During this same time period, ISIS routinely issued permits to groups in the areas under their control, allowing for the looting of archaeological and cultural heritage sites, with the permittees sharing a portion of the black-market profits with ISIS in exchange for the right to keep some of the profits for themselves. The looting of these sites and the subsequent improvements to domestic and household structures in the areas bordering the sites has been observed through analysis of satelle imagery of these locations (Casana, 2015; Parcak, 2013). In the intervening years, while the presence of ISIS in the region has been marginalized, the looting of archaeological sites continues in the destabilized region (CITE). Oftentimes, the looting of these resources is not known until months after the fact, often seen by satellite imagery or when locals discuss their activities with archaeologists returning to some of the affected areas to continue their research (Casana, 2015; Proulx, 2013). 

<img src="images/TellMardikh_Syria_2014.jpg" width="430" >  <img src="images/TellesSinn_Syria_2014.png" width="350" >

The duel impact of the loss of cultural heritage and the monies gained from their sale are motivation to find methods to intercept stolen antiquities before they reach the black market. Understanding the methods of transportation that these groups utilize is essential to understanding how they are moving goods from the initial archaeological sites, through the countries, across the borders, and into safe houses where they could be held for decades before they are sold. 

Computer simulations offer an option for this research. By first understanding the transportation options available to smugglers, simulations can be informed which can provide reliable insight on the routes that smugglers would select when transporting illicit antiquities away from looted archaeological sites. Research into transnational smuggling indicates that when transporting illicit goods, smugglers will often transport goods overland following two methods, by hiding in plain sight and/or by moving with stealth (Basu, 2013; Basu, 2014). Following the idea that smugglers will make rational informed decisions when selecting these overland routes (Basu, 2014; Medel, 2015), this project has several aims: first, to use computer simulations to identify viable routes traffickers would use based on previous literature and the application of graph theory; second, to use this data to construct two qualitative surveys designed to provide insight into the decisions participants will make when provided information on road conditions, route circuity, faction-control, crime rates, and available alternative routes, as well as how they rank the importance of these factors; and finally, to use this data to inform a link-weighting system designed to produce the least-cost paths smugglers would likely select when faced with the same decisions and a rational mind.

<img src="images/Medel2015_MXRoutes.jpg" width="350" >  <img src="images/graphtheoryexample.png" width="400" >

In an attempt to aid cultural heritage workers, international NGO's, and local stakeholders, this project addresses the problem of illicit antiquities trafficking by using computer simulations to illuminate the relationship between existing transportation infrastructures and the paths criminals use to transport stolen antiquities from archaeological sites. We believe this project will provide proof of concept that computer simulations can reliably predict the routes that smugglers would select when they choose to hide in plain sight. 

### 2.1 Motivation

The looting of historical sites is both damaging to the cultural heritage of local communities and helping fund dangerous terrorist activity in the MENA region. While there has been a large amount of research focused on drug smuggling, little has addressed the issue of artifact smuggling. This research will address this gap in the literature and potentially have real-world impact on artifact smuggling.

### 2.2 Proposed Solution

The current project will utilize graph-theory to develop a series of routes within known smuggling networks. Our modeled smuggling network will take into account highly related factors like circuity and border security in order to generate routes with better validity than what can be achieved with shortest-path routing. A series of surveys and questionnaires will be used to gain additional insight about our model and smuggling behavior. The goal is for this model of smuggling to be extended to the MENA region where it can be used to predict artifact smuggling routes.

PUT IN SECTION TO EXPLAIN THIS IS NOT THE SHORTEST PATH, BUT LEAST RISK PATH.

### 2.3 Hypotheses:

#### H1:
Incorporating region specific variables that are related to criminal behavior (faction borders, distance, crime rates, and route exposure) will lead to improved prediction of smuggling routes compared to a standard shortest-path approach. 

>> H1 Rationale: Based off previous literature, it is reasonable to believe that smugglers will take actions that help them blend in with civilians in order to avoid detection by authorities. However, in countries that are dealing with major geopolitical conflicts, standard shortest-path routes generated by a program like Google maps are not applicable. It can be difficult to predict the routes in a country with unstable infrastructure. Further, smugglers are likely to be more concerned with the presence of border security or enemy faction control in the region than they are of police presence. From this standpoint, incorporating regional specific information--like the circuity of a route or the presence of border security-- into a graph model for routing may lead to improved prediction of smuggling routes.

#### H2:
When forced to choose between competing routes, enemy faction presence will serve as the strongest deterrent towards route selection.

>> H2 Rationale: A major challenge for the current project will be validating our model against historical data. Currently, there are some documented drug smuggling routes that have been made public throughout Central and North America. These routes will be used as validation data for our model. However, drug smuggling routes may differ from artifact smuggling routes, and the drug smuggling route data is limited to begin with. Our plan is to administer a survey in which participants are asked to choose between several variations of a route. These variations will alter route characteristics like distance, faction presence, or border control.  We hope to analyze the choices made by participants to understand which variables--and to what extent these variables--contribute to common sense routing decisions. These results will also provide some insight into whether or not the routes generated by our model are realistic.

#### H3:
Geopolitical conflict will influence region-specific routes. 

>> H3 Rationale: One assumption that we are operating under is that smugglers will generally behave like ordinary citizens in order to lower their visibility to law enforcement. A concern is that--in countries with political instability--law enforcement may not serve as a detriment to smugglers if police corruption is an issue. Countries in the MENA region are dealing with drastically different political realities compared to those in Central America. To better understand how regional instability may influence smuggling and law enforcement behavior, we plan to distribute a qualitative survey to participants who have live(d) in those regions. This exploratory survey will provide insight in how smugglers may operate in those countries. 

### 2.4 Contributions:

* Develop a methodology for predicting artifact smuggling routes that can be applied in the MENA region. 
* Gain insight into smuggling behavior, including information on routing decisions and understanding the influence of geopolitical conflict on smuggling.

## 3. Related Work / Literature Review

One obstacle for predicting the routes that looters take while transporting goods away from archeological sites is understanding how the political or geographical conditions of a region could influence the routing decisions made by smugglers. While looting in the MENA (Middle East and North Africa) region deserves unique considerations because of the activity’s relationship to terrorist groups, certain behaviors might hold true  across regions (Proulx, 2013).  From this perspective, understanding looting behavior at a global level could serve to inform our model for looting in the MENA region. 
  
There is some anecdotal evidence to suggest that looters often do not take precautions to avoid detection by archeologists or law officials after they have stolen historical goods (Proulx, 2013). In this study on regional attitudes towards looting,  Proulx (2013) found that the majority of archeological field-workers come into contact with looters while working. Further, nearly half of these field-workers have been solicited by looters to purchase back stolen goods. Data from this study was aggregated from historical sites located broadly throughout the world, which provides some insight on looting activity in MENA. However, this study does not help to explain routing behavior that is dependent on border customs and region-specific faction politics. 

Transporting illegal antiquities has it's own unique set of complications (proper handling, packaging, packing) (CITE), however the methods selected to transport these items over land shares many similarities with the trafficking of other illicit goods (Alderman, 2012; Basu; 2013, Basu, 2014). Understanding how these goods are moved over land is useful in informing our transportation models and selecting appropriate variables for study.  To further our understanding of how smugglers historically move illicit goods over land, a review of current research in the field of transnational smuggling was necessary. Transnational smugglers traditionally select two methods to move goods from destination to destination, moving either with stealth or blending in with traditional supply chain movements (Basu, 2013; Basu, 2014). Traffickers make these decisions in a rational way, looking to make the most profits with the fewest risks (Medel, Lu, & Chow, 2015). Medel et al. (2015) investigated the movement of drugs from Mexico into the United States, using crime data to inform transportation prediction models. For these models, an understanding of the mindset of the drug cartels was necessary. The movement of illicit goods requires planning and precision, with traffickers often making well-informed decisions about the routes they use, taking into consideration the political environments the goods must move through, the quality of available routes, and environmental concerns that may impact transport (Medel et al., 2015). Medel et al. (2015) use these factors in conjunction with socio-demographic and crime data to define their cost for moving drugs along the road networks in Mexico. This methodology will inform our own weighting criteria.
  
In finding the most likely path that smugglers may take, we are using graph theory to help predict the routes.  In graphing theory, vertices are points (also refered to as nodes) defined with edges that connect the vertices to form a graph.  The edges can be unidirectional or bidirectional.  To use the graph theory to help in predicting the shortest route, the graph is created to represent a geographic layout of a region, in our case the southern part of Mexico.  The vertices represents the cities that are along the various routes that the smugglers could take.  The edges represents the paths between the cities which are the major roadways that connect the cities.  By defining the veriticies and edges to represent the geographic routes in Mexico, a graph is created to help in determining the most likely route smugglers would take.
  
In order to find the most likely route using graph theory, the route with the smallest weighted path will be found.  To accomplish this, the edges (which represents the routes between the cities) will be given weights based on some attributes.  These attributes will include the following:

* Crime rate
* Distance
* Circuity
* Population
* Cartel controlled

These attribures will defined the weight given to each edge in the graph. In our research, these attributes have been used in other research for predicting paths smugglers would take in Mexico (Medel et al., 2015).

With the graph constructed and weights applied to the edges, the shorted route can be found.  Although the shortest route can be found manually, there are algorithms that can find the shortest path.  One such algorithm is Dijkstra’s Algorithm (Rodríguez-Puente & Lazo-Cortés, 2013) which will be used to determine the shortest path though the graph.  The Dijkstra’s Algorithm used with a graph tree simulation program can determine the shortest path given the input quickly.  The route determined by the Dijkstra’s Algorithm will represent the best route, not based on distance, but based on lowest risk to the smuggler.  
  
## 4. Research Method

As previously mentioned, the current project aims to address the lack of information surrounding smugglings routes in the MENA region by developing a model that can identify the most-likely long-distance pathways taken by smugglers. These pathways will consider attributes that are favorable for trafficking in addition to considering the standard least-distance/least-time approach. This will be the initial step in developing a more robust model that can be applied to the MENA region in future research. 
 
* First, using a similar approach as Medel (2015), a graph model will be created that considers distance, faction presence, crime rate, and route circuity. Based on the drug smuggling literature,  these regional crime statistics likely contribute to the routing decisions made by organized criminal networks. 

* Next, we will attempt to gauge the extent that each of these variables influence travel-patterns in the real world.  For this topic, two qualitative surveys will be administered to human subjects. The data gathered will be used to inform our model inputs as well as inform any future attempts to apply this methodology to problem areas in the MENA region. 

### 4.1 Participants

We anticipate drawing from two separate participant populations: one sample from the general college population and the other from participants living in the MENA region. For the college student sample, 30 undergraduate students (age 18+) will be recruited using the University of Central Florida's SONA research system. These students will be asked to complete a short questionnaire on routing decisions.

From the MENA region, 30 adults (18+) who live (or who have lived) in the region will be recruited through Facebook advertisement. It is expected that a portion of these participants will be nonrespondents due to the nature of the content on the survey. 

### 4.2 Materials

At current, two questionnaires have been developed to address [hypothesis 2](######h2:) and [hypothesis 3](######h3:). 

The first, the Route Decision Questionnaire, is composed of two major sections. In the first section, participants will be provided a brief historical context on the project and the issue of looting in the MENA region. Then, they will be asked to take on the perspective of a smuggler to rank the importance of our variables of interest (crime rate, faction presence, circuity, and distance traveled). The second section of the survey will present the participant with various routes and ask them to choose the route that they believe provides the strongest opportunity for success. Each of the 5 questions in this section will consists of 3 routes that have varying attributes related to the section 1 of the survey.

The second questionnaire, titled the Regional Influence Questionnaire, will be distributed to participants in the MENA region. This survey was developed to probe topics related to corruption and smuggling as they relate to our routing model. The survey consists of 10 structured-interview style questions will multiple choice response. The bottom of the survey will have a section for free-response comments.

## 5. Study Plan and Procedure 

### 5.1 Routing Model

Drawing from the methods developed by Medel (2015), our graph model will be developed using a high-level overview of Central America. In the graph, nodes will represent major waypoints located throughout the region. These waypoints will consist of several dozen major cities, towns, and highway entrances. Using a qualitative approach, historical data will be gathered on the crime rate and criminal faction presence of that node's surrounding area. This data will be systematically applied to that nodes edges. 

### Inset flow chart here

Links between nodes will represent the pathway between major waypoints. As a base, these links will be given a value that corresponds to the distance between nodes. Then, this distance will be weighted by crime rate and faction presence of connected nodes. Once this network has been established, routing will be completed using Dijkstra's shortest path algorithm. Because the distance between nodes was weighed by our regional variables, this model will represent the path of least-cost.

<img src="images/MX_NodesLinks_Alpha.jpg" width="500" >

### 5.2 Surveys

Intro

#### 5.2.1 IRB Plan

Insert form here (maybe) or explain how/why we choose the type to do

#### 5.2.2 Route Decision Questionnaire

Participants recruited through SONA will be asked to fill out the questionnaire in a face-to-face session. The function of an in-person meeting is to ensure that any questions from the participant concerning this nuanced cultural issue can be fully addressed be researchers. After receiving a thorough briefing on the topic, participants will be allowed to complete the paper-based form in private. This questionnaire is not expected to take more than 15 minutes to complete. 

#### 5.2.3 Regional Influence Questionnaire

Participants will be recruited through Facebook and social media. Respondents who choose to participate will receive a link to fill out the survey through Google Forms. Study's completed in this manner are both convenient and anonymous. Survey completion will take no more than 10 minutes. 

<img src="images/Reg_Infl_Survey_pg1.JPG" width="425" ><img src="images/Reg_Infl_Survey_pg2.JPG" width="425" >

### 5.3 Define Routes

A set of routes were taken from previous studies, mainly the Medel study which showed the routes that were predicted along a path from a cartel controlled area to the US-Mexico border as shown below.  The Medel study included many factors to come up with the least expensive route that the trafficers may take while traveling.  Using the study as a reference, our project focused on finding the most likely path from the Mexican city of Zihuatanejo in the Pacific coast to Nuevo Laredo, which shares the border with Laredo, TX.

<img src="images/MedelRoutes.png" width="400">

A map was studied showing the major road networks between Zihuatanejo to Nuevo Laredo.  Major population cities along the path were picked out to form the road netowrk and cities that the smugglers would have to travel though.  The cities were plotted into Google Earth along with the linear routes between the cities that matched the road networks that connect the cities.  The result is shown below.

<img src="images/RoutesKMZ.png" width="300">

### 5.3 Route and City Information

With the cities defined, informatin was gathered about each city to start to form the attributes that will be applied to the routes when generating the various weights.  It was choosen to use the destination city's information to apply to the route's attributes when calculating the weights.  

City information of crime rate and population was found using crime data that reported the crime rate and population for each city (“Mexico Crime Map,” n.d.).  Cartel information was gathered showing which cartels control different areas PUT REFERENCE IN HERE.  This map was overlayed onto the route maps to allow us to determine which cartels control the different areas for each city.

<img src="images/RoutesWithCartel.png" width="400">

The city information was collected with the following information.  

| City | Crime Rate | Population | Cartel | 
| --- | --- | --- | --- | 
| Aguascalientes | 6.8 | 905908 | Tierra Caliente | 
| Celaya | 38.2 | 513690 | Tierra Caliente | 
| Ciudad Valles | 19.5 | 184262 | Tamaulipas | 
| Ciudad Victoria | 29.3 | 368317 | Tamaulipas | 
| Fresnillo | 42.3 | 231904 | Tamaulipas | 
| Guadalajara | 22.5 | 1538374 | Shared | 
| Huetamo | 28.6 | 49031 | Tierra Caliente | 
| Irapuato | 53.7 | 584276 | Tierra Caliente | 
| La Piedad | 22.3 | 107696 | Tierra Caliente | 
| León | 26.5 | 1575400 | Tierra Caliente | 
| Linares | 0 | 89441 | Tamaulipas | 
| Matehuala | 21.4 | 102579 | Tamaulipas | 
| Monclova | 6.7 | 240033 | Tamaulipas | 
| Monterrey | 17.1 | 1226064 | Shared | 
| Morelia | 41.2 | 786782 | Tierra Caliente | 
| Nueva Ciudad Guerrero | 0 | 5371 | Tamaulipas | 
| Nueva Italia de Ruiz | 4.7 | 42605 | Tierra Caliente | 
| Nuevo Laredo | 15.2 | 432926 | Tamaulipas | 
| Pátzcuaro | 14.7 | 95335 | Tierra Caliente | 
| Piedras Negras | 7.1 | 168297 | Tamaulipas | 
| Reynosa | 30.9 | 718857 | Tamaulipas | 
| Rioverde | 10 | 100293 | Tamaulipas | 
| Sabinas | 2.9 | 69718 | Tamaulipas | 
| Sabinas Hidalgo | 10.3 | 38888 | Tamaulipas | 
| Saltillo | 3.2 | 825244 | Tamaulipas | 
| San Juan de los Lagos | 13.3 | 74932 | Tierra Caliente | 
| San Juan del Río | 13.5 | 280960 | Tierra Caliente | 
| San Luis Potosí | 20.4 | 854014 | Tamaulipas | 
| San Tiburcio | 0 | 548 | Tamaulipas | 
| Torreón | 11.1 | 723100 | Sinaloa | 
| Uruapan | 74.6 | 348643 | Tierra Caliente | 
| Zacatecas | 36.3 | 148752 | Tamaulipas | 
| Zamora | 62.9 | 200205 | Tierra Caliente | 
| Zihuatanejo | 103.8 | 132894 | Tierra Caliente |

The routes were defined next using the maps that were generated.  Each route was given a name of a from and to city.  The routes linear distance was measured using Google Earth.  The routes road distance was calculated using Google Maps.  These two attributes were used to calculate the circuity of the route by dividing the path distance by the linear distance.  The destination city's crime rate and population was also tabulated for the routes.

| Route | Linear Distance (mi) | Path Distance (mi) | Circuity | Destination City Crime Rate | Destination Population |
| --- | --- | --- | --- | --- | --- |
| Zihuatanejo to Huetamo | 75.9 | 162 | 2.1 | 28.6 | 49031 |
| Zihuatanejo to Nueva Italia de Ruiz | 97.4 | 125 | 1.3 | 4.7 | 42605 |
| Nueva Italia de Ruiz to Uruapan | 25.3 | 36.2 | 1.4 | 74.6 | 348643 |
| Huetamo to Morelia | 74.2 | 128 | 1.7 | 41.2 | 786782 |
| Uruapan to Pátzcuaro | 26.9 | 35.5 | 1.3 | 14.7 | 95335 |
| Pátzcuaro to Morelia | 27.6 | 33.7 | 1.2 | 41.2 | 786782 |
| Morelia to San Juan del Río | 85.6 | 151 | 1.8 | 13.5 | 280960 |
| Morelia to Celaya | 57.3 | 90.4 | 1.6 | 38.2 | 513690 |
| Morelia to Irapuato | 65.8 | 86.6 | 1.3 | 53.7 | 584276 |
| Celaya to Irapuato | 34.1 | 42.2 | 1.2 | 53.7 | 584276 |
| Irapuato to Celaya | 34.1 | 42.2 | 1.2 | 38.2 | 513690 |
| San Juan del Río to Celaya | 49.9 | 65.6 | 1.3 | 38.2 | 513690 |
| Celaya to San Juan del Río | 49.9 | 65.6 | 1.3 | 13.5 | 280960 |
| Pátzcuaro to La Piedad | 58.4 | 132 | 2.3 | 22.3 | 107696 |
| Uruapan to Zamora | 40.9 | 64.9 | 1.6 | 62.9 | 200205 |
| Zamora to La Piedad | 25.6 | 32.7 | 1.3 | 22.3 | 107696 |
| La Piedad to Irapuato | 46.9 | 61.5 | 1.3 | 53.7 | 584276 |
| Zamora to Guadalajara | 82 | 104 | 1.3 | 22.5 | 1538374 |
| La Piedad to Guadalajara | 83.8 | 103 | 1.2 | 22.5 | 1538374 |
| La Piedad to León | 56.4 | 69.6 | 1.2 | 26.5 | 1575400 |
| Irapuato to León | 38.8 | 43.1 | 1.1 | 26.5 | 1575400 |
| San Juan del Río to San Luis Potosí | 134 | 159 | 1.2 | 20.4 | 854014 |
| Celaya to San Luis Potosí | 105 | 160 | 1.5 | 20.4 | 854014 |
| Irapuato to San Luis Potosí | 101 | 128 | 1.3 | 20.4 | 854014 |
| León to San Luis Potosí | 82.4 | 112 | 1.4 | 20.4 | 854014 |
| Guadalajara to San Juan de los Lagos | 70.3 | 89.2 | 1.3 | 13.3 | 74932 |
| San Juan de los Lagos to San Luis Potosí | 102 | 119 | 1.2 | 20.4 | 854014 |
| León to San Juan de los Lagos | 38.5 | 50.6 | 1.3 | 13.3 | 74932 |
| San Juan de los Lagos to León | 38.5 | 50.6 | 1.3 | 26.5 | 1575400 |
| San Juan del Río to Rioverde | 105 | 255 | 2.4 | 10 | 100293 |
| Rioverde to San Luis Potosí | 62.6 | 109 | 1.7 | 20.4 | 854014 |
| San Luis Potosí to Rioverde | 62.6 | 109 | 1.7 | 10 | 100293 |
| San Juan del Río to Ciudad Valles | 121 | 231 | 1.9 | 19.5 | 184262 |
| Rioverde to Ciudad Valles | 61.3 | 75.8 | 1.2 | 19.5 | 184262 |
| Ciudad Valles to Rioverde | 61.3 | 75.8 | 1.2 | 10 | 100293 |
| Ciudad Valles to Matehuala | 152 | 166 | 1.1 | 21.4 | 102579 |
| San Luis Potosí to Matehuala | 101 | 121 | 1.2 | 21.4 | 102579 |
| Ciudad Valles to Ciudad Victoria | 117 | 143 | 1.2 | 29.3 | 368317 |
| Ciudad Victoria to Linares | 80.2 | 96.7 | 1.2 | 0 | 89441 |
| Matehuala to Linares | 104 | 142 | 1.4 | 0 | 89441 |
| Linares to Monterrey | 72.7 | 80.9 | 1.1 | 17.1 | 1226064 |
| Monterrey to Sabinas Hidalgo | 48 | 64.8 | 1.4 | 10.3 | 38888 |
| Sabinas Hidalgo to Nuevo Laredo | 77.7 | 81.7 | 1.1 | 15.2 | 432926 |
| Monterrey to Nueva Ciudad Guerrero | 86 | 108 | 1.3 | 0 | 5371 |
| Nueva Ciudad Guerrero to Nuevo Laredo | 66.1 | 78.1 | 1.2 | 15.2 | 432926 |
| Monterrey to Reynosa | 125 | 136 | 1.1 | 30.9 | 718857 |
| Reynosa to Nueva Ciudad Guerrero | 62.7 | 81.7 | 1.3 | 0 | 5371 |
| Guadalajara to Aguascalientes | 103 | 138 | 1.3 | 6.8 | 905908 |
| San Juan de los Lagos to Aguascalientes | 41.9 | 50.8 | 1.2 | 6.8 | 905908 |
| Aguascalientes to Zacatecas | 57.2 | 73.2 | 1.3 | 36.3 | 148752 |
| Guadalajara to Zacatecas | 149 | 199 | 1.3 | 36.3 | 148752 |
| San Luis Potosí to Zacatecas | 107 | 120 | 1.1 | 36.3 | 148752 |
| Guadalajara to Fresnillo | 172 | 217 | 1.3 | 42.3 | 231904 |
| Zacatecas to Fresnillo | 29.5 | 37.8 | 1.3 | 42.3 | 231904 |
| Zacatecas to San Tiburcio | 113 | 127 | 1.1 | 0 | 548 |
| Matehuala to San Tiburcio | 63.6 | 73.9 | 1.2 | 0 | 548 |
| San Tiburcio to Saltillo | 92.3 | 108 | 1.2 | 3.2 | 825244 |
| Matehuala to Saltillo | 121 | 158 | 1.3 | 3.2 | 825244 |
| Saltillo to Monterrey | 43.7 | 54.2 | 1.2 | 17.1 | 1226064 |
| Fresnillo to Torreón | 166 | 205 | 1.2 | 11.1 | 723100 |
| Saltillo to Torreón | 149 | 157 | 1.1 | 11.1 | 723100 |
| Torreón to Saltillo | 149 | 157 | 1.1 | 3.2 | 825244 |
| Torreón to Monclova | 153 | 229 | 1.5 | 6.7 | 240033 |
| Saltillo to Monclova | 106 | 123 | 1.2 | 6.7 | 240033 |
| Monterrey to Monclova | 105 | 121 | 1.2 | 6.7 | 240033 |
| Monclova to Sabinas | 67 | 71.4 | 1.1 | 2.9 | 69718 |
| Sabinas to Piedras Negras | 63.8 | 75.6 | 1.2 | 7.1 | 168297 |
| Piedras Negras to Nuevo Laredo | 103 | 110 | 1.1 | 15.2 | 432926 |

### 5.3 Graph Tea Writeup

Write up a little about Graph Tea.  Then show a pic of the routes and cities in Graph Tea.

## 6. Results

### 6.1 Route Decision Questionnaire Responses

The results for the questionnaire was gathered from a pilto study using the class as subjects.  The Score and Ranking attribute were averaged among the results.  The Low/High was taken by using the value that had the majority of the responses.  The averaged information is shown below.

| Attribute | Score | Low/High | Ranking |
| --- | --- | --- | --- |
| Presence of Competing Gangs | 4.71 | Low | 1.86 |
| Distance to Next Desination | 3.86 | Low | 2.43 |
| Crime Rate | 3.14 | High | 3.14 |
| Population Density | 2.86 | Low | 3.71 |
| Complexity of the Route | 2.86 | Low | 3.86 |

### 6.2 Regional Influence Questionnaire Response

Write up about the responses.

### 6.3 Calculating Attribute Weights

To apply the weights of the different attributes, scales were applied to each attribute.  The scale was based on the Ranking attribute that was dirived from the Route Decision Questionnaire.  These scales will be used against each routes attributes to detemine the final weighting of the attribute.

| Attribute | Weight Scale |
| --- | --- |
| Distance Weight | 400 |
| Circuity Weight | 100 |
| Crime Weight | 300 |
| Population Weight | 200 |
| Cartel Weight | 500 |

Each destination city was assigned a cartel that controlled the particular area.  For this projected, it was assumed that the begining city of Zihuatanejo was the control cartel, with a weighting of 1.  If a city was in a rival cartel area, then the cartel weighting was set to 0.  If the city had shared or multiple controls from cartels, it was given a partial weighting of 0.33 since there were three cartels in the study.

| Cartel | Weighting |
| --- | --- |
| Shared | 0.33 |
| Sinaloa | 0 |
| Tamaulipas | 0 |
| Tierra Caliente | 1 |

Each of the routes attributes were normalized to range from 0 to 1.  The assending or dessending order was based on the Low/High response from the Route Decision Questionnaire results.  Each attribute was then scaled by the attribute scale and summed.  The results for each route is shown below.

| Route | Distance | Circuity | Crime | Popluation | Cartel | Route Weight |
| --- | --- | --- | --- | --- | --- | --- |
| Zihuatanejo to Huetamo | 0.3 | 0.21 | 0.38 | 0.97 | 0.00 | 449 |
| Zihuatanejo to Nueva Italia de Ruiz | 0.38 | 0.83 | 0.06 | 0.97 | 0.00 | 449 |
| Nueva Italia de Ruiz to Uruapan | 0.1 | 0.72 | 1. | 0.78 | 0.00 | 567 |
| Huetamo to Morelia | 0.29 | 0.51 | 0.55 | 0.5 | 0.00 | 433 |
| Uruapan to Pátzcuaro | 0.11 | 0.81 | 0.2 | 0.94 | 0.00 | 369 |
| Pátzcuaro to Morelia | 0.11 | 0.88 | 0.55 | 0.5 | 0.00 | 396 |
| Morelia to San Juan del Río | 0.34 | 0.48 | 0.18 | 0.82 | 0.00 | 401 |
| Morelia to Celaya | 0.22 | 0.62 | 0.51 | 0.67 | 0.00 | 440 |
| Morelia to Irapuato | 0.26 | 0.81 | 0.72 | 0.63 | 0.00 | 525 |
| Celaya to Irapuato | 0.13 | 0.86 | 0.72 | 0.63 | 0.00 | 481 |
| Irapuato to Celaya | 0.13 | 0.86 | 0.51 | 0.67 | 0.00 | 428 |
| San Juan del Río to Celaya | 0.2 | 0.81 | 0.51 | 0.67 | 0.00 | 447 |
| Celaya to San Juan del Río | 0.2 | 0.81 | 0.18 | 0.82 | 0.00 | 377 |
| Pátzcuaro to La Piedad | 0.23 | 0.12 | 0.3 | 0.93 | 0.00 | 379 |
| Uruapan to Zamora | 0.16 | 0.61 | 0.84 | 0.87 | 0.00 | 552 |
| Zamora to La Piedad | 0.1 | 0.84 | 0.3 | 0.93 | 0.00 | 399 |
| La Piedad to Irapuato | 0.18 | 0.81 | 0.72 | 0.63 | 0.00 | 496 |
| Zamora to Guadalajara | 0.32 | 0.84 | 0.3 | 0.02 | 0.67 | 643 |
| La Piedad to Guadalajara | 0.33 | 0.87 | 0.3 | 0.02 | 0.67 | 648 |
| La Piedad to León | 0.22 | 0.87 | 0.36 | 0. | 0.00 | 281 |
| Irapuato to León | 0.15 | 0.96 | 0.36 | 0. | 0.00 | 263 |
| San Juan del Río to San Luis Potosí | 0.53 | 0.9 | 0.27 | 0.46 | 1.00 | 974 |
| Celaya to San Luis Potosí | 0.41 | 0.66 | 0.27 | 0.46 | 1.00 | 904 |
| Irapuato to San Luis Potosí | 0.4 | 0.84 | 0.27 | 0.46 | 1.00 | 916 |
| León to San Luis Potosí | 0.32 | 0.78 | 0.27 | 0.46 | 1.00 | 880 |
| Guadalajara to San Juan de los Lagos | 0.28 | 0.84 | 0.18 | 0.95 | 0.00 | 438 |
| San Juan de los Lagos to San Luis Potosí | 0.4 | 0.92 | 0.27 | 0.46 | 1.00 | 925 |
| León to San Juan de los Lagos | 0.15 | 0.81 | 0.18 | 0.95 | 0.00 | 385 |
| San Juan de los Lagos to León | 0.15 | 0.81 | 0.36 | 0. | 0.00 | 247 |
| San Juan del Río to Rioverde | 0.41 | 0. | 0.13 | 0.94 | 1.00 | 892 |
| Rioverde to San Luis Potosí | 0.25 | 0.5 | 0.27 | 0.46 | 1.00 | 821 |
| San Luis Potosí to Rioverde | 0.25 | 0.5 | 0.13 | 0.94 | 1.00 | 875 |
| San Juan del Río to Ciudad Valles | 0.47 | 0.38 | 0.26 | 0.88 | 1.00 | 982 |
| Rioverde to Ciudad Valles | 0.24 | 0.87 | 0.26 | 0.88 | 1.00 | 937 |
| Ciudad Valles to Rioverde | 0.24 | 0.87 | 0.13 | 0.94 | 1.00 | 910 |
| Ciudad Valles to Matehuala | 0.6 | 0.97 | 0.29 | 0.94 | 1.00 | 1108 |
| San Luis Potosí to Matehuala | 0.4 | 0.89 | 0.29 | 0.94 | 1.00 | 1020 |
| Ciudad Valles to Ciudad Victoria | 0.46 | 0.88 | 0.39 | 0.77 | 1.00 | 1042 |
| Ciudad Victoria to Linares | 0.31 | 0.89 | 0. | 0.94 | 1.00 | 903 |
| Matehuala to Linares | 0.41 | 0.77 | 0. | 0.94 | 1.00 | 929 |
| Linares to Monterrey | 0.29 | 0.96 | 0.23 | 0.22 | 0.67 | 657 |
| Monterrey to Sabinas Hidalgo | 0.19 | 0.78 | 0.14 | 0.98 | 1.00 | 890 |
| Sabinas Hidalgo to Nuevo Laredo | 0.3 | 1. | 0.2 | 0.73 | 1.00 | 928 |
| Monterrey to Nueva Ciudad Guerrero | 0.34 | 0.85 | 0. | 1. | 1.00 | 919 |
| Nueva Ciudad Guerrero to Nuevo Laredo | 0.26 | 0.91 | 0.2 | 0.73 | 1.00 | 900 |
| Monterrey to Reynosa | 0.49 | 0.97 | 0.41 | 0.54 | 1.00 | 1026 |
| Reynosa to Nueva Ciudad Guerrero | 0.25 | 0.82 | 0. | 1. | 1.00 | 879 |
| Guadalajara to Aguascalientes | 0.4 | 0.79 | 0.09 | 0.43 | 0.00 | 353 |
| San Juan de los Lagos to Aguascalientes | 0.16 | 0.88 | 0.09 | 0.43 | 0.00 | 266 |
| Aguascalientes to Zacatecas | 0.22 | 0.83 | 0.49 | 0.91 | 1.00 | 1000 |
| Guadalajara to Zacatecas | 0.58 | 0.79 | 0.49 | 0.91 | 1.00 | 1140 |
| San Luis Potosí to Zacatecas | 0.42 | 0.95 | 0.49 | 0.91 | 1.00 | 1089 |
| Guadalajara to Fresnillo | 0.67 | 0.85 | 0.57 | 0.85 | 1.00 | 1195 |
| Zacatecas to Fresnillo | 0.12 | 0.83 | 0.57 | 0.85 | 1.00 | 970 |
| Zacatecas to San Tiburcio | 0.44 | 0.95 | 0. | 1. | 1.00 | 971 |
| Matehuala to San Tiburcio | 0.25 | 0.92 | 0. | 1. | 1.00 | 891 |
| San Tiburcio to Saltillo | 0.36 | 0.91 | 0.04 | 0.48 | 1.00 | 844 |
| Matehuala to Saltillo | 0.47 | 0.82 | 0.04 | 0.48 | 1.00 | 879 |
| Saltillo to Monterrey | 0.17 | 0.86 | 0.23 | 0.22 | 0.67 | 602 |
| Fresnillo to Torreón | 0.65 | 0.87 | 0.15 | 0.54 | 1.00 | 999 |
| Saltillo to Torreón | 0.58 | 1. | 0.15 | 0.54 | 1.00 | 986 |
| Torreón to Saltillo | 0.58 | 1. | 0.04 | 0.48 | 1.00 | 941 |
| Torreón to Monclova | 0.6 | 0.68 | 0.09 | 0.85 | 1.00 | 1004 |
| Saltillo to Monclova | 0.42 | 0.92 | 0.09 | 0.85 | 1.00 | 954 |
| Monterrey to Monclova | 0.41 | 0.93 | 0.09 | 0.85 | 1.00 | 953 |
| Monclova to Sabinas | 0.26 | 0.99 | 0.04 | 0.96 | 1.00 | 906 |
| Sabinas to Piedras Negras | 0.25 | 0.9 | 0.1 | 0.89 | 1.00 | 897 |
| Piedras Negras to Nuevo Laredo | 0.4 | 0.99 | 0.2 | 0.73 | 1.00 | 966 |

### 6.4 Graph Tea (Change the name) Results

Write how Graph Tea works.  Record a video of the Graph Tea running.  Show the final result in Graph Tea.  Show the result in KMZ.

Graph Tea was used to calculate the route with the least risk calcualted on based on the routes attributes and survey results.  The cities were loaded into Graph Tea in their respective geographical locations.  The routes were defined using the city to city routes with the weights defined from the results each routes attributes and the weighting determined by the Route Decision Questionnaire results.  The input in the Graph Tea program is shown below.

<img src="images/GraphTeaInput.png" width="400">

<img src="images/MexicoRoutes85.mp4">

## 7. Conclusion

### 7.1 Compare to other studies results

## 8. Future Work

### 8.1 Expand this to use more turn-by-turn simulation

### 8.2 Apply to MENA

## References

Alderman, K. L. (2012). Honor Amongst Thieves: Organized Crime and the Illicit Antiquities Trade. Indiana Law Review, 45, 27.

Basu, G. (2013). The role of transnational smuggling operations in illicit supply chains. Journal of Transportation Security, 6(4), 315–328. https://doi.org/10.1007/s12198-013-0118-y

Basu, G. (2014). The strategic attributes of transnational smuggling: Logistics flexibility and operational stealth in the facilitation of illicit trade. Journal of Transportation Security, 7(2), 99–113. https://doi.org/10.1007/s12198-013-0132-0

Casana, J. (2015). Satellite imagery-based analysis of archaeological looting in Syria. Near Eastern Archaeology, 78(3), 142–152.

Luke, Christina, and Morag Kersel. (2005). A Retrospective and a Look Forward. Journal of Field Archaeology, 30(2), 191-200.

Medel, M., Lu, Y., & Chow, E. (2015). Mexico’s drug networks: Modeling the smuggling routes towards the United States. Applied Geography, 60, 240–247. https://doi.org/10.1016/j.apgeog.2014.10.018

Mexico Crime Map. (n.d.). Retrieved November 16, 2019, from Crimenmexico website: https://elcri.men/en/municipios-map.html

Parcak, Sarah, David Gathings, Chase Childs, Greg Mumford, and Eric Cline. (2016). Satellite Evidence of Archaeological Site Looting in Egypt: 2002–2013. Antiquity, 90(349), 188–205.

Proulx, B. B. (2013). Archaeological Site Looting in “Glocal” Perspective: Nature, Scope, and Frequency. American Journal of  Archaeology, 117(1), 111. https://doi.org/10.3764/aja.117.1.0111

Rodríguez-Puente, R., & Lazo-Cortés, M. S. (2013). Algorithm for shortest path search in Geographic Information Systems by using reduced graphs. SpringerPlus, 2(1). https://doi.org/10.1186/2193-1801-2-291

Terrill, W. Andrew. (2017). Antiquities Destruction and Illicit Sales as Sources of ISIS Funding and Propaganda. Carlisle, PA: U.S. Army War College. 
