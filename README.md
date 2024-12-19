# Introduction
Save Our Children is a global NGO committed to improving children's well-being around the world through healthcare, education and other economic development programs. The NGO recently got a generous donation of 20 million USD and the Board of Directors have agreed to use this donation to reduce the world's infant mortality rate.

# Problem Statement
To ensure that this donation is going to the most needy nations, the organization's data science team has been tasked with identifying the top 10 countries that will benefit the most from these funds. Although , there are many ways to address this problem,the lead data scientist believes that performing a K-means clustering analysis using demographic and socio-economic factors will be an efficient way of determining these top 10 countries.This notebook uses K-means to categorize countries of the world into low to high infant mortality regions and afterwards ranks the countries in the high infant mortaliity region to select the top 10 countries that Save Our Children NGO should focus on.

# Datasets
Two datasets were used for this analysis. Demographic and socio-economic factors by country data was obtained from the UNESCO Institute for Statistics and country classifications by income level data was obtained from the World Bank (worldbank.org). The UNESCO dataset contained numerous factors data from 2017 -2023. For this analysis,a subset of factors were first chosen and then exploratory data analysis was done to identify the factor that when plotted against infant mortality rate showed the most promise of resulting in a succesful clustering analysis. These factors was then used for the clustering analysis. Also to ensure the analysis reflect current reality, only the most recent year data was used and the world bank dataset was used to crosscheck the results of the clustering analysis.

# Workflow
Exploring the datasets
Data Cleaning
Exploratory Data Analysis
Feature Scaling
K-means clustering analysis
Results and visualization
Conclusion and recommendations
