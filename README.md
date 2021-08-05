# Data606Capstone
Crime Prediction in Baltimore


An unfortunate reality is the existence and frequency of crime. Baltimore city is ranked at fourth place for most dangerous cities in the United States. In 2019 there was a 1 in 55 chance that you will be a victim of a violent crime (rape, sexual assault, robbery, assault, and murder).  Prediction of potential crime and occurrence  offers a potential solution to the city.  Predicting crimes occurrences is important to the community because protective and preventative measures may be implemented. Understanding what and when a crime may occur will give government and community leaders a more accurate approach to correcting root causes of the dillema. For example, understanding that robberies occur at a greater frequency at a specific location can be beneficial to the local government in understanding why it is happening and how to resolve it.


Data Set
API where I will be calling real time data to be used in the model: https://egis.baltimorecity.gov/egis/rest/services/GeoSpatialized_Tables/Part1_Crime/FeatureServer/0/query?where=1%3D1&outFields=*&outSR=4326&f=json

The data is being called from Baltimore Open Data (https://data.baltimorecity.gov/)  a public data hub that allows users the ability to observe, interact, and analyze data regarding the city of Baltimore. If historical data does not suffice to train the model, documented crime data in CSVs may be merged to the original dataset via SQL join function. The data types contained in the data set are ints, varchar, floats, coordinates, and datetime. 

The unit of analysis for this project will be 

Story
With Black Lives Matter at the peak of its movement in the United States, data sources and evidence regarding police interactions will be extremely useful as evidence to address the situations that are impacting our nation. A machine learning model will predict and define the crime occurrence as to allow what type of resources to utilize for the interaction. For example, if domestic disputes or drug usage is predicted as the majority occurrence for a month by the model, the police department may increase counselors or individuals specialized in conflict resolution. Having a higher number of these specialized team members to be dispatched to an area will be of greater service than an officer who may potentially raise the level of tension. According to the American Community Survey (https://worldpopulationreview.com/us-cities/baltimore-md-population) Baltimore, Maryland demographic consists of an approximate 62.35% Black and African American  population. With Black Lives Matter  protests historically and currently occurring in Baltimore, this majority demographic population would greatly benefit from the results of the model. If successful this model may be used with crime data  from other cities, states, and counties to help lift the burden that our nation and many are facing. 


Hypothesis / Research Question(s)
Using the features present in the dataset (RowID, CrimeDateTime, CrimeCode, Location, Description, Inside_Outside, Weapon, Post, District, Neighborhood, Latitude, Longitude, GeoLocation, Premise, VRIName, Total_Incidents) I will create a model that can predict crime occurance, location, and type. If the machine is trained on enough data then it may predict an occurance of a possible crime.
