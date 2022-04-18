# Amazon_Vine_Analysis
## Overview of the analysis: 
The goal of the analysis is to analyze the Amazon reviews written by members of the paid Amazon Vine program. This program allows manufacturers to recive reviews. Vine members get small incentives to write reviews. This specific data set contains revoews for Amazon kitchen products. The data was then transformed used ETL process in pyspark to determine if there is any bias toward favorable review from vine members.


## Results: Using bulleted lists and images of DataFrames as support, address the following questions:
#### Total Number of Reviews

<img width="732" alt="image" src="https://user-images.githubusercontent.com/94877067/163749156-2714bcb9-53ed-472b-b6de-3342d8568050.png">


#### Number of Vine member  Reviews

<img width="914" alt="image" src="https://user-images.githubusercontent.com/94877067/163749325-1e3476f6-8c4b-4861-8026-2b11f42a92ae.png">

#### Number of non vine member  reviews


<img width="695" alt="image" src="https://user-images.githubusercontent.com/94877067/163749429-efc7f4ae-5388-4d14-b3a5-84c2e739543b.png">

#### Total 5 star reviews

<img width="680" alt="image" src="https://user-images.githubusercontent.com/94877067/163750432-b4c830f8-27c2-47b3-8944-06c0fea371d6.png">

#### Percentage of 5 star review from Vine members

<img width="562" alt="image" src="https://user-images.githubusercontent.com/94877067/163750501-1af5bc5a-ca40-46cc-ad4b-31b7dcae22ee.png">


#### Percentage of 5 star review from non Vine members

<img width="431" alt="image" src="https://user-images.githubusercontent.com/94877067/163750516-51194222-4ea4-4e92-993f-4d9389767a29.png">



## Summary:

In summary there was no bias in 5 star rating from vine paid members as the percentage of 5 star rating from non vine members was high
