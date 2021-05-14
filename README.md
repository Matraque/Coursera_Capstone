# Coursera_Capstone
This Notebook is used for the Coursera capstone Project - IBM Data Science

# WHERE TO OPEN A CRAFT BEER BAR IN PARIS? 
## Using data science to find the best location


## Introduction:

### Background 

The craft beer movement, a trend imported from the United States, is spreading all around Europe and is growing steadily in France, originally considered as a wine country. The insatiable demand for quality craft beer led to the creation of more and more microbreweries and beer bars specialized in craft beer over the past 15 years.  

### Goals

Through data science, the following analysis tries to define the most favorable districts to establish a craft beer bar in Paris, France. Using data analysis, data visualization and machine learning, we will narrow down neighborhoods in Paris based on different criteria: 

First, we want our bar to be located in an attractive and vibrant area of Paris, with an active nightlife. The presence of other nearby venues will attract people and create traffic. 
On the other hand, as our concept represents a niche (craft beer lovers), we want to avoid the presence of direct competitors in the same neighborhood. 
At last, Paris is a very expensive city and the exorbitant real estate prices can be a barrier to entry for opening a business. Thus, we will focus on neighborhoods whose prices match our budget. 

This analysis represents a draft market study for a business plan or an executive summary. It is intended for potential entrepreneurs who want to better understand the market of craft beer pubs in Paris by providing a data-driven insight into the best locations, based on specific criteria. 

### Data:

Paris is divided in 20 boroughs called “Arrondissements” and 80 neighborhoods. Data about boroughs and neighborhoods is available online. It can be found for free at https://www.data.gouv.fr/fr/datasets/quartiers-administratifs/ and https://datafrance.info/paris-75000. We will be using geographical coordinates for each neighborhood, their name and average price per Square Meter. 

To compare neighborhoods among each other’s, we will use the Foursquare API that list all venues in specific areas. We will then be able to cluster the neighborhoods based on their similarities using unsupervised machine learning technique to select the best fit for our craft beer pub. 
