# Overview
This is a project based on a dataset involving accidents recorded from 1960 to 2023

# Business Understanding

The project is based on the question that a company is seeking to venture into the aviation industry and would like to understand the risks it may face in the industry

The stakeholders in this business understanding would be:

a)the shareholder of the companny
b)the procuremnt department of the company
c)management department of the company
d)risk analysis department of the company

The analysis would be trying to answer the following questions that the stakeholders may be interested in

a)an overview of the number of accidents in the aviation industry through the years
b)a recommendation of the type of aircraft they should search consider when procuring aircrafts for their new venture

# Data understanding

## Source of data

The data was sourced from the National Transportation Safety Board and was accessed through the kaggle website.
The data contained information on aviation accidents recorded from 1962 to 2023

## Description of data

The data contained two datasets

a) aviation_data = contains the actual data we are going to use in our database

b)US state codes = contains the full names of abreviated states

For this analysis we will be only using the aviation data

### aviation data

The aviation data contained 31 columns and 88889 rows.
Each column provides more information on the accident referenced for example:

a)make
b)model
c)weather condition
d)phase of flight etc

The data did not contain a lot of null values and due to the fact most of the data was categorical data it was best to remove the rows that contained the null values


### Data Visualisations

#### distribution of accidents over number years
![No of aviation accident through the years](<images/No of accidents through the year.png>)

The diagram above shows that the number of accidents has declined through the years

#### The top 10 companies and their top 3 models involved in the most accidents

![The top 10 aeroplane companies and their top most models involved in accidents](<images/Aeroplane make and model and number of accidents.png>)

The diagram shows that the aeroplane company named Cessna produces the highest amount of aeroplanes models that are involved in accidents

#### Number of engine types involved in accidents and the type of weather that was occurring

![Engine types involved in accident and the weather that was occuring](<images/engine_type,weather conditions vs number of accidents.png>)

The diagram shows that the reciprocating engine is the most poor in various weather conditions


# Conclusion

The analysis of the data shows that the number of accidents has reduced throughout the years. This has mainly been led by the improved technology in the building of aeroplanes and the aviation laws that govern the industry

The analysis could not come up with a particular best plane due to the lack of enough data i.e 

a)cost of aircrafts make and model
b)cost of operating and aircraft
c)type of aircraft

This therefore makes it difficult in recommending an exact aircraft but we are able to recommend that the company should be weary on purchasing Cessna aircrafts and aircrafts with reciprocating engines


# Tableau links
For extra visulalisations proceed to the following link

link:https://public.tableau.com/app/profile/stephen.mungai/viz/Analysisofaeroplanesaccidents/Aeroplanesaccident?publish=yes










