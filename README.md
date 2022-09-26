# How far can you go for love on Airbnb? - The effect of Valentine's Day on Airbnb listings

Welcome to our research project! This research aims to answer the following research question:

**What is the effect of Valentine's Day on Airbnb listings in Europe?**

![This is an image](https://turntable.kagiso.io/images/romantic_bedroom.width-800.jpg)

## Motivation
Valentine's day is celebrated yearly on the 14th of February. It is a day when romance takes centre stage and people show their love for each other with accompanying rituals. Specific behaviours and rituals that people often perform are giving gifts, showing affection, or going out for dinner or a romantic getaway [(Close & Zinkhan, 2006)](https://www.acrwebsite.org/volumes/v33/v33_10020.pdf). For overnight stays, Airbnb accommodation is often booked.

Therefore, this study proposes the following research question:

*What is the effect of Valentine's Day on Airbnb listings in Europe?*

We zoom in on several major cities in Europe. This is interesting because not every country celebrates Valentine's Day to the same extent and/or not every city is equally popular. In addition, we look at whether it matters whether Valentine's Day falls on a weekend or not. For example, if Valentine's Day falls on a Monday, people may be less inclined to book an overnight stay than if it falls on a Friday. It is then possible that guests might postpone their overnight stays until the weekend.

This leads to the following sub-questions:
- What is the effect of Valentine's Day on the price of Airbnb listings in 'city'?
- Which type of accommodation is booked more than usual on Valentine's Day in 'city' and by how much?
- Is there a difference in the number of bookings on Airbnb on Valentine's day than any other day in February?
- What is the difference between Valentine's day bookings in 'city A' and 'city B' (different cities in Europe) looking at price/accomodation type? <sub>--> can expand with more cities</sub>
- How does the popularity of Valentine's Day in the city/country influence Airbnb bookings, looking at price/accommodation type? <sub>--> note: find/create a separate dataset for this question to combine with Airbnb data.</sub>

<sub>note: (laatste twee zijn beetje hetzelfde misschien)</sub>

We expect that here would be more demand for Airbnb listings around this holiday. If demand increases, hosts can charge higher prices for their accomodations. Moreover, more accommodations for 2 people are likely to be booked, as couples usually celebrate Valentine's Day.

## Data
The data used in this research project was obtained from [Inside Airbnb](http://insideairbnb.com/). For this research, we looked into the data starting from two weeks before Valentine's Day 2022 (January 31st) untill two weeks after Valentine's day 2022 (February 18th) February (year). We created a dummy variable that indicates whether it is Valentine's Day or not. This allows us to compare the effect of Valentine's Day with other, 'normal' days. 

## Method and results
**Method**

As discussed above Data from Inside Airbnb will be used to look at different cities in Europe regarding their Airbnb listings in the month of februari and especially Valentine's Day. The analysis of the Airbnb data will start with the city Amsterdam, and will later expand to doing the same analysis for other cities in Europe. --> note: for other cities definetely include city of love: Paris

Analysis:

Several ANOVA analyses?

Variables:

DV: price, accomodation type/characteristics, number of bookings

IV: Valentine's Day

Moderator: city (size)

![Conceptual model](https://user-images.githubusercontent.com/91567676/192151644-fab4ce64-46ab-46e4-8eb9-367f85869462.png)

**Results**

## Repository overview
```
├── README.md
├── data
├── gen
│   ├── analysis
│   ├── data-preparation
│   └── paper
└── src
    ├── analysis
    ├── data-preparation
    └── paper
```
## Running instructions


## More resources


## About

This research project is part of the [Data Preparation and Workflow Management (dPrep)](https://dprep.hannesdatta.com/) course at Tilburg University and is conducted by Team 12. The contributors of the research are: [Anouk Bor](https://github.com/AnoukBor), [Eva Bos](https://github.com/EvaBos), [Bi Xuan Guo](https://github.com/bixuanguo), [Mandana Khabbazi](https://github.com/Mandanakhabbazi), [Indi Wieggers](https://github.com/indiwieggers123).
