---
layout: page
title: Housing Data Analysis
subtitle: Understanding the rental analysis through geospatial visualisation
---

# <span style="color: #D35400 ;">General Analysis</span>

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
  1. In general, the more people that stay in a house, the cheaper it will be. 
  2. Individual rent appears to be directly linked to shared areas.


### <span style="color: #BA4A00 ;">Discussion of these findings</span>
#### More People, Cheaper Rent
 - The only outlier is four or more bedroom types, which as discussed in the methodology have been assumed to all be four bedroom houses with four tenants, the most stringent assumption of tenancy.
 - This would result in an overestimation of the price for four or more bedroom houses. Notably, this means that the observation that the median rent of four or more bedroom houses being cheaper than one bedroom, studio, and two bedroom houses is even more significant, as even with this overestimation it is still cheaper than the three types.

#### Share More, Less Rent
 - One bedroom and studio type houses can be understood to be the most expensive given that amenities such as toilets and kitchen are only owned, used, and rent paid by one tenant.
 - With two or more bedroom type houses having these amenities have shared ownership, use, and rent split with other tenants.
 - Finally, standalone rooms can be observed to be the cheapest because the tenant does not have any ownership of these amenities under their room rent.

### Rents and Prices

Looking at the number of rents and prices, we can conclude the following:
 1. Three Bedrooms are well balanced between cheap rent and amenities, as well as decent availablility in the housing market. Four or more Bedrooms could also be a cost-effective alternative, and possibly cheaper than three bedrooms.
 2. Two Bedrooms are the most available house type at middle of the range prices, a good option for those looking to urgently find a house.
 3. One Bedroom and Studios are the most expensive house types, best for individuals who enjoy full ownership and sole use of their amenities. One bedrooms are more available than studios, although this comes at an increased cost, albeit likely with more floor space.
 4. Standalone rooms are the cheapest house type, although it comes at a cost of having no ownership of one's amenities.


# <span style="color: #D35400 ;">Price Analysis by Borough</span>

First, a overall picture of the London housing market is provided by mapping prices by borough.

<iframe width="120%" height="1100" src="https://jaoshang.github.io/QM2groupproject/assets/boroughprices.html"></iframe>


# <span style="color: #D35400 ;">Price Analysis by Configuration</span>

We then mapped out the individual rent prices for various room configurations, being arranged by how likely people consider such configurations based on our previous conclusions.
Referring to them can provide an indication of which boroughs of London have been historically cheaper to rent certain house types.

## One Bedroom


<iframe width="120%" height="1100" src="https://jaoshang.github.io/QM2groupproject/assets/One Bedroom.html"></iframe>


A innovative solution to make one bedrooms a more-cost effective option could be for couples to move in together, as done in many Asian countries, to split rent. This would also benefit from having a greater prevalence of one bedroom listings.


<iframe width="120%" height="1100" src="https://jaoshang.github.io/QM2groupproject/assets/One Bedroom Shared.html"></iframe>


## Three Bedroom


<iframe width="120%" height="1100" src="https://jaoshang.github.io/QM2groupproject/assets/Three Bedroom.html"></iframe>

 
<iframe width="120%" height="1100" src="https://jaoshang.github.io/QM2groupproject/assets/Three Bedroomindiv.html"></iframe>


## Studio


<iframe width="120%" height="1100" src="https://jaoshang.github.io/QM2groupproject/assets/Studio.html"></iframe>


## Two Bedroom


<iframe width="120%" height="1100" src="https://jaoshang.github.io/QM2groupproject/assets/Two Bedroom.html"></iframe>

 
<iframe width="120%" height="1100" src="https://jaoshang.github.io/QM2groupproject/assets/Two Bedroomindiv.html"></iframe>


## Four or more Bedroom


<iframe width="120%" height="1100" src="https://jaoshang.github.io/QM2groupproject/assets/Four or more Bedrooms.html"></iframe>

 
<iframe width="120%" height="1100" src="https://jaoshang.github.io/QM2groupproject/assets/Four or more Bedroomsindiv.html"></iframe>


## Standalone Room

<iframe width="120%" height="1100" src="https://jaoshang.github.io/QM2groupproject/assets/Room.html"></iframe>

