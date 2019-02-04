# RA_BLOS_Umich

# BICYCLIST PERCEIVED LEVEL OF TRAFFIC STRESS: A QUALITY OF SERVICE MEASURE

#### Author: Charlene Mingus, Georgia Institute of Technology, May 2015 

#### Feb. 31, 2019
#### Draft Review


# Contents

- [Introduction](#introduction)
- [Research Background](#research-background)
    - [Bicyclist-Typology](#bicyclist-typology)
        - [ABC Bicyclists (Skill level)](#abc-bicyclists-skill-level)
        - [Level of User Skill and Comfort](#level-of-user-skill-and-comfort)
        - [Bicycling Frequency](#bicycling-frequency)
        - [Stated Comfort Level: Four Types of Cyclists](#stated-comfort-level-four-types-of-cyclists)
        - [Sociodemographic and the Four Types of Cyclists](#sociodemographic-and-the-four-types-of-cyclists)
    - [Variables That Influence the Choice to Bicycle](#variables-that-influence-the-choice-to-bicycle)
    - [Models to Estimate Bicyclist Perception of the Quality of Service of a Facility](#models-to-estimate-bicyclist-perception-of-the-quality-of-service-of-a-facility)
- [Methodology](#methodology)
        - [Typology - Cycle Atlanta LTS](#typology---cycle-atlanta-lts)
        - [Bicycle network](#bicycle-network)
        - [LTS Quality of Service Measure](#lts-quality-of-service-measure)
        - [Traffic Stress Criteria for Links](#traffic-stress-criteria-for-links)
        - [Signalized Intersections](#signalized-intersections)
        - [Criteria for Unsignalized Intersections](#criteria-for-unsignalized-intersections)
- [Case Study](#case-study)
    - [Data](#data)
    - [Model](#model)
    - [Result](#result)
- [Conclusion](#conclusion)
- [Future Research](#future-research)
    - [Criteria for Links](#criteria-for-links)
    - [Criteria for Signalized Intersections](#criteria-for-signalized-intersections)
    - [Criteria for Unsignalized Intersections](#criteria-for-unsignalized-intersections-1)
    - [Validating LTS Typology](#validating-lts-typology)
    - [Validating LTS Quality of Service Tool Criteria](#validating-lts-quality-of-service-tool-criteria)

- [Conclusion](#Conclusion)
- [Future Research](#Future-Research)
	- [Criteria for Links](#Criteria-for-Links)
	- [Criteria for Signalized Intersections](#Criteria-for-Signalized-Intersections)
	- [Criteria for Unsignalized Intersections](#Criteria-for-Unsignalized-Intersections)
	- [Validating LTS Typology](#Validating-LTS-Typology)
	- [Validating LTS Quality of Service Tool Criteria](#Validating-LTS-Quality-of-Service-Tool-Criteria)
  
<a name="Introduction"></a>
# Introduction

The objective of this study is to refine and apply a bicycle quality of service tool which will allow the assessment of transportation infrastructure design based on users’ perceived stress also known as Level of Traffic Stress (LTS). This study builds upon the Mineta Transportation Institute’s Level of Traffic Stress tool. Unlike other quality of service tools, LTS determines the stress of a route by the link or intersection with the highest link, not by the average stress. The tool was then applied to a case study area, a six mile buffer around the Atlanta BeltLine Eastside Trail in Atlanta, Georgia, to understand the facility designs and traffic conditions that create a bicycle network that people who do not currently bike, but are interested in biking would be comfortable riding on. The bicycle network includes not only facilities with bicycle specific accommodations, but also any roadway that does not prohibit bicycling by statute or regulation.

Michigan Department of Transportation and the Center for Advancing Transportation Leadership and Safety (ATLAS Center), a University Transportation Center and Collaboration between the University of Michigan Transportation Research Institute (UMTRI) and the Texas A&M Transportation Institute (TTI) sponsored by the US Department of Transportation, Research and Innovative Technology Administration (RITA) funded this research.

<a name="Research-Background"></a>
# Research Background

<a name="Bicyclist-Typology"></a>
### Bicyclist-Typology

<a name="ABC-Bicyclists-(Skill-level)"></a>
##### ABC Bicyclists (Skill level)
In a 1994 report, Selecting Roadway Design Treatments to Accommodate Bicycles, the FHWA classified cyclists based on skill level as Advanced Bicyclists, Basic Bicyclists, and Children. The recommendation was to encourage designing bicycle facilities for “B” or basic bicyclists, but the proportion of the population that could be classified into each category still needed to be quantified.

<a name="Level-of-User-Skill-and-Comfort"></a>
##### Level of User Skill and Comfort
The 2012 AASHTO Guide for the Development of Bicycle Facilities categorizes bicyclists based on age, experience and confidence. It identified two rider types: Experienced and Confident rider type which includes, “bicyclists who are comfortable riding on most types of facilities,” such as roads without any bicycle specific treatments, and riders who prefer low-traffic residential streets or separated paths; Casual and Less Confident riders, which may ride frequently for many purposes, bicycle occasionally and only ride on low-traffic streets or separated paths, ride for recreation possibly with children, or use the bicycle as a necessary mode for transportation.

<a name="Bicycling-Frequency"></a>
##### Bicycling Frequency
Winters et al: regular cyclists who cycle at least once a week; frequent cyclists who ride at least monthly; occasional cyclists who ride at least once a year; and potential cyclists who had no ridden in the previous year, but would like to ride in the future. Dill and Voros: Non-Cyclists who never ride a bicycle or who occasionally ride but did not ride during the past summer of in non-summer months; Irregular Cyclists who rode in the past summer, but not in non-summer months or those who rode year-round, but less than once a week; and Regular Year-Round Cyclists who rode year-round at least once a week.
Sanders: Non-cyclist; Infrequent cyclist; and Frequent cyclist
Ahmed et al.: Committed Cyclists and Casual Cyclists

<a name="Stated-Comfort-Level:-Four-Types-of-Cyclists"></a>
##### Stated Comfort Level: Four Types of Cyclists
Roger Geller, the City of Portland’s Bicycle Coordinator in 2006, attempted to categorize the entire population, current and potential bicyclists, by their comfort riding on different types of bicycle facilities. Four categories were then defined as.
- The Strong and Fearless: individuals who would bicycle in almost any road or traffic condition with no consideration of separated bicycle facilities.
- The Enthused and Confident: individuals who are comfortable riding in the roadway with motor vehicles but they prefer their own facilities.
- The Interested but Concerned: interested in bicycling, however, they are unwilling to bicycle on shared roadways with high motor vehicle travel speeds and traffic volumes and will only bicycle on roadways with low speeds and low traffic volumes like neighborhood roads and prefer to ride on bicycle or shared-use only facilities.
- No Way No How: people who would never considering bicycling for various reasons from physical inability to bicycle, topography, or lack of interest.
The Interested but Concerned category makes up approximately 60 percent of Portland’s population. Thus, The Portland Bicycle Master Plan stated that its target was the Interested but Concerned category. This classification was developed based on professional experience, which must be verified and refined with additional research. 
Dill and McNeil conducted a random phone survey in Portland, Oregon and verified these categories. But still, additional survey should be conducted in other cities in the U.S. to verify if the typology is applicable or other adjustments should be made. 

<a name="Sociodemographic-and-the-Four-Types-of-Cyclists"></a>
##### Sociodemographic and the Four Types of Cyclists
Misra et al. further modified the topology by dividing the Interested but Concerned category into two groups: Comfortable but Cautious and Interested but Concerned. Under this scenario, they were defined as:
- Comfortable but Cautious group: include female bicyclists and/or older bicyclists who are bicycle enthusiasts, but may be more risk adverse which makes the type appear less confident than the Enthused but Confident type.
- Interested but Concerned: contain people who were interested in bicycling, but who had significant safety concerns
The study also showed that sociodemographic characteristics, particularly age, gender, and rider history, were significant predictors of people’s self-classification into different types. Using socio-demographic characteristics to predict user type can help predict facility design needs for a city as potential cyclist’s preferences can be predicted.

<a name="Variables-That-Influence-the-Choice-to-Bicycle"></a>
### Variables That Influence the Choice to Bicycle
- Weather: temperature, precipitation and wind, no consistent influence.
- Actual and Perceived Safety: the public perception of bicycling accidents as an inescapable element of bicycling and blaming bicyclists for placing themselves in peril
-	City Size and Population Density: cities or metropolitan areas with higher levels of density have higher cycling mode share
-	Public attitude toward bicycling: people consider bicycling as abnormal in the U.S.. “Fewer bicyclists  more abnormal” is a self-perpetuating cycle. 
-	Relative Cost of Motor Vehicles and Public Transit: In the U.S., “less robust transit system” and “lower cost of utilizing a motor vehicle” both encourage the use of motor vehicles even for short trips that could be walked or biked.
-	Income and Sociodemographic: higher income level  less likely to bicycle; women bicycle less than men
-	Topography: The impact of hilliness on the decision to bicycle as compared to other variables is thought to be moderate.
-	Bicycle Parking and End of Destination Infrastructure: the availability of bicycle parking improves the cyclists’ perception and when located at transit stops encourages multi-modal trips
-	Distance from Origin to Destination: distance threshold is only being set by current bicyclists with no consideration of potential bicyclists
-	Traffic, Roadway, and Bikeway Characteristics: positive impact, Misra et al.’s research showed all cyclist types preferred separated bicycle facilities Winters analysis found that environmental and engineering factors carried the strongest influence; including facility design, safety issues, topography, scenery, and weather.

<a name="Models-to-Estimate-Bicyclist-Perception-of-the-Quality-of-Service-of-a-Facility"></a>
### Models to Estimate Bicyclist Perception of the Quality of Service of a Facility
See Excel Matrix

<a name="Methodology"></a>
# Methodology

By outlining the criteria to classify roadways and separated bicycle facilities by level of traffic stress based on geometric design and traffic characteristics, this study tried to create a quality of service measure which connects user tolerance for perceived traffic stress with roadway and bikeway characteristics that can be measured in the field.

<a name="Typology---Cycle-Atlanta-LTS"></a>
##### Typology - Cycle Atlanta LTS
The Cycle Atlanta LTS typology is used in this research as the basis for the LTS roadway and bikeway criteria which are discussed in more detail later. By associating a specific typology with LTS levels for roadway and bikeway criteria it will be possible for future research to validate the criteria based on revealed and stated preference. Misra is currently conducting research to compare the LTS classification of routes that people chose to bicycle and the Cycle Atlanta LTS typology that they identify as. This research can help refine the LTS criteria for classifying roadways and bikeways.

![Image1](https://github.com/cadtju/RABLOSUMICH/blob/master/1.png)

<a name="Bicycle-network"></a>
##### Bicycle network
In the context of this research, the bicycle network includes any facility that a bicycle is allowed to travel on from streets to shared use paths or greenways.

![Image2](https://github.com/cadtju/RABLOSUMICH/blob/master/2.png)
![Image3](https://github.com/cadtju/RABLOSUMICH/blob/master/3.png)
![Image4](https://github.com/cadtju/RABLOSUMICH/blob/master/4.png)
![Image5](https://github.com/cadtju/RABLOSUMICH/blob/master/5.png)

<a name="LTS-Quality-of-Service-Measure"></a>
##### LTS Quality of Service Measure
The LTS quality of service measure outlined below builds upon the MTI LTS. Roadways and bikeways categorized at LTS 1 are the least stressful and have low traffic volumes and low speed limits, while roadways and bikeways categorized as LTS 4 are the most stressful and have the highest traffic volumes and speed limits. It is estimated that the majority of current and potential bicyclists find LTS 1 and LTS 2 facilities comfortable.
Within the LTS quality of service measure, a person who identifies as LTS 3 will find LTS 3, LTS 2, and LTS 1 facilities comfortable, a person who identifies as LTS 2 will find LTS 2 and LTS 1 facilities comfortable and so on.
The criteria matrices follow the rule that the aspect of a link or intersection with the highest LTS determines the LTS of that segment or intersection.


<a name="Traffic-Stress-Criteria-for-Links"></a>
##### Traffic Stress Criteria for Links
Level of traffic stress was applied to links or segments between intersections for separated, protected, and on street bicycle facilities. The roadway and traffic characteristics which are considered for all roadways and bicycle facility links except for shared-use paths, side paths, and protected cycle tracks are:
1. street width or through lanes per direction, 
2. traffic volume of annual average daily traffic (AADT) and functional class 
3. posted speed limit.
4. On street Parking (data availability)
   
- Criteria for Separated Bicycle Facilities
- Criteria for Bicycle Lanes With and Without On Street Parking
- Criteria for Buffered Bike Lanes With and Without On Street Parking
- Criteria for Shared Travel Lanes

<a name="Signalized-Intersections"></a>
##### Signalized Intersections
Intersection design is a very important component of perceived level of traffic stress for users. Unfortunately, very little research has been conducted on the topic, especially intersection design for protected bicycle facilities. studies have shown that intersection crossings and right and left turns are important for bicyclist route choice. Broach, Dill, and Gliebe’s study found that bicyclists preferred intersections without traffic signals or stop signs since they increased delay. However, when traffic volume was moderate or heavy on the crossing street bicyclists in the study preferred traffic signals

<a name="Criteria-for-Unsignalized-Intersections"></a>
##### Criteria for Unsignalized Intersections

<a name="Case-Study"></a>
# Case Study
This study focused on the Atlanta BeltLine Eastside trail in Atlanta, Georgia. A six-mile buffer around the Atlanta BeltLine Eastside Trail was designated as the study area. 

<a name="Data"></a>
### Data
![Image6](https://github.com/cadtju/RABLOSUMICH/blob/master/6.png)

The RC_ROUTES_ARC attribute information had to be transferred to NAVTEQ Streets 2014 through a manual process due to the lack of common field. They further manually geocoded: the location of on street parking on roadways with conventional bicycle lanes and buffered bicycle lanes; intersections with right turn only motor vehicle lanes that connect to links with conventional bicycle lanes, buffered bicycle lanes, or protected cycle tracks, the location of bike boxes. The process was extremely time consuming.

<a name="Model"></a>
### Model
Join and relate --> Geocoding --> Buffer and Intersect --> SQL Query and Symbology (Categorization) --> Filed Calculator (Length Summary) --> Add NPU Layer --> Network Analyst (Unsignalized Intersection Analysis) --> Add the Bike Boxes Layer

<a name="Result"></a>
### Result

- Criteria for left-turning bicyclist at signalized intersections and criteria for bicycle through movement at unsignalized intersections are excluded from this map. The map has a limited number of roadways and bikeways coded blue or LTS 1, however, a large portion of the map has green or LTS 2 roadways and bikeways.

![Image7](https://github.com/cadtju/RABLOSUMICH/blob/master/7.png)
![Image8](https://github.com/cadtju/RABLOSUMICH/blob/master/8.png)

- While a majority of the roadways and bikeways in the study area are classified as LTS 1 and LTS 2, these facilities appear to not be well connected. Connectivity analysis was not conducted in this thesis. Instead an analysis of the bikeshed of the Atlanta BeltLine Eastside Trail for LTS 1 and LTS 2 facilities was completed. A bikeshed is the distance that a bicyclist can travel from a given point outward, in this case the Atlanta BeltLine Eastside Trail.
![Image9](https://github.com/cadtju/RABLOSUMICH/blob/master/9.png)

- They study then look into the connectivity between the bikesheds and different Neighborhood Planning Units (NPUs). The majority of NPU E, M, and W are not reached by the Eastside Trail LTS 1 and LTS 2 bikeshed. NPU E and M are likely to see mode share increase due to the concentration of students if low stress infrastructure is installed. 
![Image10](https://github.com/cadtju/RABLOSUMICH/blob/master/10.png)

- The next image compares the bikeshed with and without this criteria applied. The dark grey facilities are those that were included in Figure 12-14, but which were excluded in Figure 14 due to the presence of unsignalized intersections which exceeded LTS 1 and LTS 2 criteria.
![Image11](https://github.com/cadtju/RABLOSUMICH/blob/master/11.png)

<a name="Conclusion"></a>
# Conclusion
This research refined the LTS tool introduced by the MTI, however, the current and potential bicyclist typology and the design and traffic criteria used in the LTS quality of service tool should be modified.
By orienting the bicycle network toward low stress bikeways and roadways the LTS quality of service tool avoids trying to place bicycle facilities on arterials and other roadways with high traffic volume, posted speed, and number of through lanes, which are preferred for motor
vehicle traffic.
Simplifying the roadway and bikeway network assists in creating maps which can be easily read. However, the roadway and bikeway network should be developed in the future to include directionality. The primary issues with this simplification were: 
- roadway links with a bicycle facility in one direction, but not the other resulting in a lower LTS categorization
- 	intersection approaches where the bicycle facility was dropped in one direction, but not the other resulting in a higher LTS categorization for the link,
-	roadways where bicycling is restricted due to streetcar rails in one direction, but not the other resulting in an LTS categorization in a restricted access area, 
-	on street parking located by a bicycle facility in one direction by not the other resulting in a lower LTS categorization.

<a name="Future-Research"></a>
# Future Research

<a name="Criteria-for-Links"></a>
### Criteria for Links
-	Pavement Markings and Signage
-	Traffic Calming
-	Slope
-	Bicycle Lane Blockage
-	Bicycle Boulevards


<a name="Criteria-for-Signalized-Intersections"></a>
### Criteria for Signalized Intersections
-	Signalized Separated Turning Movements: Bicycle signals may be installed at signalized intersections to reduce conflict between motor vehicles and bicycles by creating separate signal phasing for motor vehicle and bicycle movements.
-	The vehicle entry point

<a name="Criteria-for-Unsignalized-Intersections"></a>
### Criteria for Unsignalized Intersections
-	Bicycle Through Movement at Unsignalized Intersections with and without a Median Refuge Island

<a name="Validating-LTS-Typology"></a>
### Validating LTS Typology
-	Reaching potential bicyclist groups

<a name="Validating-LTS-Quality-of-Service-Tool-Criteria"></a>
### Validating LTS Quality of Service Tool Criteria
-	Stated preference VS. Actual Preference
