# Coursera_Capstone
## 1. Introduction

The number of traffic crashes and their victims has been a rising trend globally due to increases in population and motorization. Every year the lives of more than 1.25 million people are cut short as a result of road traffic accidents[1]. Road traffic injuries also cause considerable economic losses to individuals, their families, and society. 

Since different factors involved in traffic crashes have a substantial effect on each other, it is difficult to individually consider any of the parameters when explaining the severity of traffic crashes. The project aims to predict the severity of car accidents based on a few factors. It can help drivers to avoid potential delays and improve the preparedness of first responders[2].

## 2. Data

The dataset (click [here](https://s3.us.cloud-object-storage.appdomain.cloud/cf-courses-data/CognitiveClass/DP0701EN/version-2/Data-Collisions.csv)) used in this project is shared data and it contains car accidents that have happened in the city of Seattle, Washington from 2004 to 2020 with a total number of 194, 673 accidents. 

There are 37 attributes except for the labeled data but we don't need all attributes for prediction of accident severity. The attributes, like  WEATHER, ROADCOND, and LIGHTCOND, can tell us the natural conditions when the accidents happen. On the contrary, attributes, like INATTENTIONIND, UNDERINFL, and SPEEDING, help us decide how these accidents take place. Then SEVERITYCODE(SEVERITYDESC) will be used as the target variable to measure the severity of each accident as to whether 1(Property Damage Only Collision) or 2(Injury Collision). In this project, the attributes mentioned above will be used to predict the severity.


[1]M. Zheng et al., "Traffic Accident’s Severity Prediction: A Deep-Learning Approach-Based CNN Network," in IEEE Access, vol. 7, pp. 39897-39910, 2019, doi: 10.1109/ACCESS.2019.2903319.

[2]Assi, K.; Rahman, S.M.; Mansoor, U.; Ratrout, N. Predicting Crash Injury Severity with Machine Learning Algorithm Synergized with Clustering Technique: A Promising Protocol. Int. J. Environ. Res. Public Health 2020, 17, 5497.
