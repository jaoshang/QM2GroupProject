---
layout: page
title: Methodology
---
After reviewing literature on the student housing market in London and noting the significant imbalance between demand and supply, we concluded that the primary aim of this research is to uncover patterns that can streamline the student accommodation search process, providing valuable insights for informed decision-making. However, we realised that analysing student housing within the London borough area would be challenging, mainly due to the constraints in effectively gathering quality data about where students actually live, which relates to ethical issues. We decided to restrict our study to UCL students and the overall housing market, since there is no difference in price and distribution of housing between student renting and normal renting.

## Importing libraries
For any visualisation being made, the first step was always to import the libraries we would use. In this case, these were:

1. <strong>Numpy</strong>
2. <strong>Pandas</strong>
3. <strong>Matplotlib</strong>
4. <strong>Seaborn</strong>

These libraries are for better support with matrices and arrays, data manipulation, making plots and greater customisation of these plots.

<p align="center"> <img src="img/Screenshot 2024-01-14 at 10.15.18.png" alt="Image Alt Text" width="400" /> </p>

## Data Cleaning
Cleaning and correcting raw data improves its quality, accuracy, and reliability for analysis or other purposes. The goal of data cleaning is to ensure that data is free from errors, duplicates, inconsistencies, and other issues that might affect its usability. In our project, the rent data and crime data will be cleaned by applying python, they will be presented in two different data frames.

We import our rent data and crime data respectively and clean them as follows:

<strong>Rent</strong>

<p align="center"> <img src="img/Screenshot 2024-01-14 at 10.27.11.png" alt="Image Alt Text" width="800" /> </p>
<p align="center"> <img src="img/Screenshot 2024-01-14 at 10.28.25.png" alt="Image Alt Text" width="500" /> </p>

The rent data after cleaning will be presented in the dataframe with columns including information on time period, category, and summary statistics of the rents. We defined our study period as 2012-2018 based on the data available, measuring by year. The dataset includes prices in respect to different types of accommodation, i.e., studio,one bedroom apartment within borough area.

<strong>Crime</strong>

<p align="center"> <img src="img/Screenshot 2024-01-14 at 10.44.57.png" alt="Image Alt Text" width="800" /> </p>
<p align="center"> <img src="img/Screenshot 2024-01-14 at 10.46.04.png" alt="Image Alt Text" width="500" /> </p>

The crime data after cleaning by python is presented in a dataframe with columns including the information of time of crime, crime locations, and crime types. After cleaning, we remain with data of borough-specific crime rates, making our analysis more feasible.



