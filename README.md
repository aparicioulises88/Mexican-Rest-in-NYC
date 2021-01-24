# Mexican-Rest-in-NYC

Introduction

New York City's demographics show that it is a large and ethnically diverse metropolis. It is the largest city in the United States with a long history of international immigration. New York City was home to nearly 8.5 million people in 2018, accounting for over 40% of the population of New York State and a slightly lower percentage of the New York metropolitan area, home to approximately 23.6 million. Over the last decade the city has been growing faster than the region. The New York region continues to be by far the leading metropolitan gateway for legal immigrants admitted into the United States.
This final project explores the best locations for Mexican restaurants throughout the city of New York. As New York is the most diverse city in the world (800 languages are spoken in New York), it has a long tradition of different ethnical restaurants. Mexican restaurants have become extremely popular, as they offer a wide variety of dishes and specially tacos. Tacos is the big reason Americans love a Mexican place because it is something different than an American burger. Tacos can be prepared in so many different ways and other Mexican dishes are also extremely popular. Americans loves margaritas and tequila so that's why potentially the owner of a Mexican restaurant can have great success and consistent profit. However, as with any business, opening a new restaurant requires serious considerations and is more complicated than it seems from the first glance. In particular, the location of the restaurant is one of the most important factors that will affect whether it will have success or a failure. So, our project will attempt to answer the questions “Where should the investor open a Mexican Restaurant?” and “Where should I go If I want great Mexican food?”

Data

In order to answer the above questions, data on New York City neighborhoods, boroughs to include boundaries, latitude, longitude, restaurants, and restaurant ratings and tips are required.
New York City data containing the neighborhoods and boroughs, latitudes, and longitudes will be obtained from the data source: https://cocl.us/new_york_dataset
All data related to locations and quality of Mexican restaurants will be obtained via the FourSquare API utilized via the Request library in Python.

Methodology
• Data will be collected from https://cocl.us/new_york_dataset and cleaned and processed into a dataframe.
• FourSquare be used to locate all venues and then filtered by Mexican restaurants. Ratings, tips, and likes by users will be counted and added to the dataframe.
• Data will be sorted based on rankings.
• Finally, the data be will be visually assessed using graphing from Python libraries.

Problem Statement
1.	What is / are the best location(s) for Mexican restaurant in New York City?
2.	In what Neighborhood and/or borough should the investor open a Mexican restaurant to have the best chance of being successful?
3.	Where would I go in New York City to have the best Mexican food?
