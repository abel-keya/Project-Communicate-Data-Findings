# Project-Communicate-Data-Findings
  
 ![G1](G1.gif) 
 
# Problem statement:
Apply design and data visualization principles to the data analysis process by creating visualizations to tell a story with data.

#
[Dataset](https://github.com/abel-keya/Project-Communicate-Data-Findings/blob/master/house_prices.csv):

In this project i used the **house_prices** provided in the workspace .The dataset has the following features:
The dataset contains 6028 records, and 7 columns.
 
* price - Price of the house
* bedrooms - Number of Bedrooms
* bathrooms - Number of Bathrooms
* style-the archtectural style of the house
* Neighborhood-the surroundig area where the house located.

# Main findings from the exploratory data analysis
I undertook exploratory data analysis by going through the following steps:
* Univariate Analysis
* Bivariate Analysis
* Multivariate Analysis

From the initial plots i discovered that a postive correlation exists between price which can be well handled with Feceted grids. As a result i put in more efforts in Multivariate faceted plot.
 
* There is a strong positive correlation between price,style and area in all the three neighbohood 
* High correlation between area,bathrooms,bedrooms, and price
* The house prices increases with the increase int the number of bedrooms, with the 8 bedrooms having the highest price figure while 1 bedroom has the lowest.This is surprising because the houses with 0 bedroom have higher prices compared to the 1 bedroom house
* There are 3 main house styles which have variation in prices in relation to the Neighborhood and house bedrooms/bathroomsVictorian Style is the most popular with the highest percentage approximately 50%, Ranch is the second most popular house styles with approximately 29.9%, Lodge style is least popular accounting to approximately 20.4 %

* Neighborhood B is the most popular with the highest percentage representation at approximately 40.26%,Neighborhood A follows with * * * approximately 31 % while Neighborhood C is the least popular with approximately 28.6%

# Choice of the results to put in the explanatory analysis


I chose  results on :
* price distribution
* price variation with respect Number of bedrooms,bathrooms,Neighborhood and styles
This is because the above factors are intertwined and each has an effect to the choice of a house and demand.


# Feedback from others for your explanatory designs.

I shared my slide deck with a course mate who made the following observiations:

* The color theme was consitent throughout the slide deck
* whether i could do feature engineering to find the price per unit area
* The reviwer was able to notice the trends in prices, the positive correlation between the price and other features
* Detailed feedback was as follows:

[6:35 PM, 6/21/2020] Data Analyst: The following are my observations: 
- From your slide deck, I can see that more focus is on exploratory analysis which has been well documented. In addition, the visualizations are well labeled. 

- In the visualizations, a couple of things come up:
    - The use of different colors in the bar chart visualizing the styles seems unnecessary since the visualization is about one measurement.
    - In the chart showing the Price versus bedrooms, labels are not well visible. Consider probably increasing the figure size.
    - In the chart visualizing bedrooms versus neighborhood, from my opinion, it would be prudent to use distinct colors (Like those you've used in the styles vs neighborhoods) to represent the neighborhoods, as the colors you've chosen seem to morph into one another, which tends to distort the information being represented. For a color blind person per se, he'd only see the dominant blue color.
    - In the distribution of bedrooms against style, it'd be prudent to have the legend at the top far end, left or right of the chart, as having it in the middle clashes with the bar representation of the 2 bedroomed houses with the lodge style. 
    - There seems to be a missing link in the line plot comparing the number of bedrooms to the area of the house.
 
In general, from the analysis and visualizations, what do you think is the main factor affecting the price of a house? Factor in having no multicollinearity between the variables.
[6:45 PM, 6/21/2020] Data Analyst: Also, There's some missing information in the text explaining the distribution of styles against  Neighborhoods. Which neighborhood has the lowest proportion of styles?

# List of resources used during the creation of the project.

* 1.https://julienbeaulieu.gitbook.io/wiki/sciences/programming/data-analysis/data-visualization/univariate-exploration-of-data/bar-chart
* 2.https://www.darkhorseanalytics.com/blog/data-looks-better-naked
* 3.https://www.oreilly.com/library/view/python-for-data/9781449323592/ch04.html
* 4.http://dataviztalk.blogspot.com/2016/02/how-to-add-jitter-to-plot-using-pythons.html
* 5.https://socviz.co/gettingstarted.html
* 6.http://yunus.hacettepe.edu.tr/~burkay.genc/courses/pss707_eda/ggplot/ggplot.html#introduction
* 7.http://cs-tklab.na-inet.jp/~tkouya/python/scipy-lectures/intro/matplotlib/matplotlib.html
* 8.https://matplotlib.org/3.1.0/tutorials/colors/colormaps.html

# Requirements
* Anaconda installation
* Google colab
* Setup instruction
> * Save a copy of the notebook in your drive and open it to access.

<p align="center">
   
   # Technologies used:
   
 <p align="center"> 
   
  <img   src="https://github.com/abel-keya/week8_IP_Abel_Keya_Nairobi-Hospital-conducted-a-clinical-camp-to-test-for-hypothyroidism/blob/master/tech3.jpg" width="550" height="300"  alt="DS" title="Requirements" />
 
</p>

# Support
In case of any clarifications or suggestions with regards to this project email me at jumakeya@gmail.com

License
Copyright (c) 2020 **Abel Keya**
