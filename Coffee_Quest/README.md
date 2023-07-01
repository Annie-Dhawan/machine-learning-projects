# Coffee Quest: Navigating Toronto's Busy Streets for the Perfect Coffee Shop Spot

## Project Summary

__Goal__: 
- To figure out the best locations for opening up a new coffee shop in Toronto City.

__Target Audience__: 
- Entrepeneurs, Business Owners, Stakeholders, Data Scientists

__Datasets__:
- [1st Data]: The most updated record of traffic signal vehicle and pedestrian volumes in Toronto City. 
- [2nd Data]: The most updated record of crime incidents reported in Toronto City provided by Toronto Police Services.
- [3rd Data]: The list of Toronto neighborhoods represented by postal codes and their boroughs. 
- [4th Data]: The popular or most common venues of a given neighborhood in Toronto. 


The followings are the step by step process for working with the project:

### 1. Web Scraping: Toronto Postal Codes

We will start the project by scraping the following Wikipedia page.
https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M

Objective:
- Obtain the data inside the html page containing a list of Toronto postal codes in the form of table and transform the data into a pandas dataframe!

### 2. Coordinate Retrieval: Toronto Postal Codes

Objective:
- Now, we will get the latitude and the longitude coordinates of each neighborhood in order to utilize the Foursquare location data later in the separate main project notebook.



### 3.  Segment & Cluster Toronto Neighborhoods

Objective:
- We will __explore__, __segment__, and __group neighborhoods__ into clusters to find similar neighborhoods in __Toronto City__. As far as this project is concerned, we will use the __Foursquare location dataset__ and use __Foursquare API__ to access it.


### 4. The Main Project Notebook

Objective: 
- Compile everything to acomplish the project's goal.


Thank you
