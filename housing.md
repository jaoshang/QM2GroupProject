---
layout: page
title: Housing Data Analysis
subtitle: Understanding the rental analysis through geospatial visualisation
---

# General Analysis

From housing dataset of Q2 of 2011 to Q1 of 2019, we plot the number of rents and prices by house type to help understand the relative availability and prices of different house types.

## Number of Rents
![Rents by Room Type](assets/img/rentplot.png)

From the graph, we can interpret the following:
 - Two Bedrooms is the most prevalent house type, with 432,659 total listings.
 - One Bedrooms is the second most prevalent house type, with 312,607 listings.
 - Three Bedrooms is the third most prevalent house type, with 181,265 listings.
 - Four or More Bedrooms, standalone rooms, and studios have similarly low levels of being rented.

At a glance, the implications of this are not very clear, only being which houses are more likely to be found in the overall market. But, we will combine this with price data, which should give us some clearer implications.

## Prices
Graphing price data, we can see the median rent that an individual would pay staying in each house type.

![Prices by Room Type](assets/img/priceplot.png)

From the graph, we can interpet the following:
  - In general, the more people that stay in a house, the cheaper it will be. The only outlier is four or more bedroom types, which as discussed in the methodology have been assumed to all be four bedroom houses with four tenants, the most stringent assumption of tenancy. This would result in an overestimation of the price for four or more bedroom houses. Notably, this means that the observation that the median rent of four or more bedroom houses being cheaper than one bedroom, studio, and two bedroom houses is even more significant, as even with this overestimation it is still cheaper than the three types.
  - Individual rent appears to be directly linked to shared areas. One bedroom and studio type houses can be understood to be the most expensive given that areas such as toilets and kitchen are only used by one tenant. With two or more bedroom type houses having these areas have shared ownership and rent split with other tenants. Finally, standalone rooms can be observed to be the cheapest because the tenant does not have any ownership nor pay rent for these areas under their room rent.

# Price Analysis by Borough

<iframe width="120%" height="1100" src="https://jaoshang.github.io/QM2groupproject/assets/boroughprices.html"></iframe>

### My story

To be honest, I'm having some trouble remembering right now, so why don't you just watch [my movie](https://en.wikipedia.org/wiki/The_Princess_Bride_%28film%29) and it will answer **all** your questions.
