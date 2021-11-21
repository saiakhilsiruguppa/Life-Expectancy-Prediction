# Life Expectancy Prediction (Using Data from WHO)

Although there have been lot of studies undertaken in the past on factors affecting life expectancy considering demographic variables, income composition and mortality rates. It was found that affect of immunization and human development index was not taken into account in the past. Also, some of the past research was done considering multiple linear regression based on data set of one year for all the countries. Hence, this gives motivation to resolve both the factors stated previously by formulating a regression model based on mixed effects model and multiple linear regression while considering data from a period of 2000 to 2015 for all the countries. Important immunization like Hepatitis B, Polio and Diphtheria will also be considered. 

In a nutshell, this study will focus on immunization factors, mortality factors, economic factors, social factors and other health related factors as well. Since the observations this dataset are based on different countries, it will be easier for a country to determine the predicting factor which is contributing to lower value of life expectancy. This will help in suggesting a country which area should be given importance in order to efficiently improve the life expectancy of its population.

# Data Description
The dataset I will be using is about Life expectancy of different countries. The goal is explore how immunization factors, mortality factors, economic factors, social factors and other health related factors affect Life expectancy of a country.

Features :

Year : from 2000 to 2015
Status : Developed or Developing status
Adult_Mortality : Adult Mortality Rates of both sexes (probability of dying between 15 and 60 years per 1000 population)
Alcohol : Alcohol, recorded per capita (15+) consumption (in litres of pure alcohol)
percentage_expenditure : Expenditure on health as a percentage of Gross Domestic Product per capita(%)
BMI: Average Body Mass Index of entire population
Total_expenditure: General government expenditure on health as a percentage of total government expenditure (%)
Diphtheria: Diphtheria tetanus toxoid and pertussis (DTP3) immunization coverage among 1-year-olds (%)
HIV_AIDS: Deaths per 1000 live births HIV/AIDS (0-4 years)
GDP: Gross Domestic Product per capita (in USD)
Population
Income_composition_of_resources: Human Development Index in terms of income composition of resources (index ranging from 0 to 1)
Schooling: Number of years of Schooling(years)

Target:
Life_expectancy: Life Expectancy in age

# Inspiration
The data-set aims to answer the following key questions:

- Does various predicting factors which has been chosen initially really affect the Life expectancy? What are the predicting variables actually affecting the life expectancy?
- Should a country having a lower life expectancy value(<65) increase its healthcare expenditure in order to improve its average lifespan?
- How does Infant and Adult mortality rates affect life expectancy?
- Does Life Expectancy has positive or negative correlation with eating habits, lifestyle, exercise, smoking, drinking alcohol etc.
- What is the impact of schooling on the lifespan of humans?
- Does Life Expectancy have positive or negative relationship with drinking alcohol?
- Do densely populated countries tend to have lower life expectancy?
- What is the impact of Immunization coverage on life Expectancy?
