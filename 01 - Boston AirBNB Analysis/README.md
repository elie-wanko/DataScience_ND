# A sneak peek into Airbnb's activites in Boston and Seattle

## Content
<li><a href="#Requirements">Requirements</a></li>
<li><a href="#project_motivation">Project Motivation</a></li>
<li><a href="#file_descriptions">File Descriptions</a></li>
<li><a href="#findings">Findings</a></li>
    <ul>
    <li><a href="#perception">1. Perception of the Customers of the Different Types of Hosts </a></li>
    <li><a href="#neighbourhood_dist">2.1 Where are the more expensive neighbourhoods concentrated in each city? </a></li>
    <li><a href="#host_dist">2.2 Which neighbourhoods are prefferred by the hosts with several listings?</a></li>
    <li><a href="#amenities_diff">3. Which are the main differences between Boston and Seattle regarding the amenities announced?</a></li>
    <li><a href="#features_predict">4. Which features are more iportant to predict the price of a listing?</a></li>
    </ul>
<li><a href="#acknowledgements">Acknowledgements</a></li>

<a id='Requirements'></a>
## Requirements
All necessary librairies can be found in [requirements.txt](https://github.com/elie-wanko/DataScience_ND/blob/master/01%20-%20Boston%20AirBNB%20Analysis/requirements.txt)

<a id='project_motivation'></a>
## Project Motivation
In this project we are going to try to answer to the following queries based on [Boston](https://www.kaggle.com/airbnb/boston) and [Seattle](https://www.kaggle.com/airbnb/seattle/data) datasets from Kaggle:

1. Perception of customers based on reviews received for the different types of hosts? We will distinguish three types of hosts here `The Opportunist(TO)`, `The Stable Extra Income Seeker(SEI)` and `The Full-Time Rentrepenur(FTR)` customers:

    * __The Opportunist__ is an Airbnb host who is willing to rent out available space from their current residence for premium or only when they know they’re not utilizing the space. They usually have a very specific time window in mind that they’re willing to rent out their unit.

    * __The Stable Extra Income Seeker__ is an Airbnb host who wants to achieve a consistent, recurring stream of extra income from their unit by renting it out on a regular, but still not full-time basis.  Maybe they want to rent out 2 weekends every month or two months every summer.
    
    * __The Full-Time Rentrepreneur__ is an Airbnb host who is renting at least one dedicated, full-time short term rental.  This is someone who seeks to ultimately have rental income from their units become their primary (or only) source of income.   They aim to operate an entire portfolio of dedicated short term rentals so they develop systems to automate as much as possible.

2. Explore the geographical distribution of the listings in the two cities and find out which neighbourhoods are more expensive neighbourhoods in each city. 

3. Main differences between Boston and Seattle listings.

4. Key features to predict the price of a listing.

<a id='file_descriptions'></a>
## File Descriptions
The following Airbnb activity is included in this Boston dataset:

* Listings, including full descriptions and average review score
* Reviews, including unique id for each reviewer and detailed comments
* Calendar, including listing id and the price and availability for that day

## Inspiration
* Can you describe the vibe of each Boston neighborhood using listing descriptions?
* What are the busiest times of the year to visit Boston? By how much do prices spike?
* Is there a general upward trend of both new Airbnb listings and total Airbnb visitors to Boston?
For more ideas, visualizations of all Boston datasets can be found [here](http://insideairbnb.com/boston/).

<a id='findings'></a>
## Findings

<a id='perception'></a>
### 1. Perception of the Customers of the Different Types of Hosts

<a id='neighbourhood_dist'></a>
### 2.1 Where are the more expensive neighbourhoods concentrated in each city?

<a id='host_dist'></a>
### 2.2 Which neighbourhoods are prefferred by the hosts with several listings?

<a id='amenities_diff'></a>
### 3. Which are the main differences between Boston and Seattle regarding some of the features announced?

<a id='features_predict'></a>
### 4. Which features are more iportant to predict the price of a listing?

<a id='acknowledgements'></a>
## Acknowledgement
* This dataset is part of Airbnb Inside, and the original source can be found [here](http://insideairbnb.com/get-the-data.html).
* The curated data set used for analysis was taken from Kaggle [here](https://www.kaggle.com/airbnb/boston)
