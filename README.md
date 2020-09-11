# MEDIUM BLOG POST: https://medium.com/@malavhirenshah/decoding-data-without-using-machine-learning-well-almost-bbc6ccb32c67

# Airbnb-August-2020-Listings-Austin
Assessing, Cleaning, Analyzing, Modeling and Visualize the Airbnb Austion Listing data from August 2020

## Contents

### 1. Libraries Used

* pandas
* numpy
* seaborn
* matplotlib
* sklearn
* shapely
* geopandas

### 2. Motivation

‘Data is the new oil.’ You’ve probably heard this over a thousand times but it is more true now than it has ever been before. Every company and individual businesses collect all kinds of data, ranging from really basic things like ‘how many times you pick up the phone in a day?’ to things like ‘What is it that you watch on Netflix the most?’. They collect these data points to understand a plethora of things ranging from consumer liking to spending habits etc. This helps them target a particular set of customers for their products and increase their revenues (It is all about the $$$).

Many a times, these datasets look like just a bunch of information tagged together but it is important to decode interesting connections between these data points. This could particularly be helpful if you are an individual looking to start a business but do not know who your target audience exactly is or if you just want to know something that might help you make some decisions i.e. where to stay, what to buy etc. Rather than just targeting random clusters of people and then realizing that this is not my target audience and having to start again, knowing a bit about ‘Who would like what and why?’ will definitely help.

I often come across people who correlate decoding data with having Machine Learning knowledge. I get questions like — ‘ Hey, I don’t know Machine Learning so how do I understand how attribute A connects to attribute B?’ Machine Learning helps, sure but that shouldn’t be deterrent for you to start exploring data.

My idea behind this project is just that. The only thing that you need to start decoding data is to come up with some ‘interesting’ questions that you want to know the answer for. This is often the hard part but once you get through this, you get a better understanding of what and how you can use the data to answer those questions.

I do end the project with a Machine Learning model that answers prediction questions but that is just to show how we can evolve from using simple concepts to answer basic questions before going on to complex scenarios.

### 3. File descriptions

* airbnb_august.ipynb - Jupyter notebook containing the code for everything from assessing, cleaning, analyzing, modeling and visualizing the airbnb dataset.  
* listings_2.csv - Airbnb August 2020 Austin dataset.
* TxDOT_City_boundaries. * - all files related to the map that is created for Q2 (geopandas and shapely)

### 4. Analysis

The airbnb_august.ipynb contains analysis for the four business and real life questions that have been posted with a logical layout of the explanation of all of them. The four questions that I answer are:

* Q.1 Do people staying at superhosts’ homes actually have better experiences than those who don’t? <br/>
  --  Use various techniques like groping and wrangling data to answer this question and can be summarized that people living at superhosts homes actually do have better experiences.
* Q.2 Is location a major factor that influences how an Airbnb is priced? <br/>
  -- Use the geopandas and shapely features along with some data manipulation to visually show the points on a map and answer that question. Summary being we can see that except a few locations, points of both the colors overlap each other heavily which suggests that although location is a factor, it is certainly not the most important one relating to the price of the Airbnb.
* Q.3 What are the most common types of amenities offered by the Airbnb’s in Austin? <br/>
  -- Use various feature transformation methods on the 'amenities' column to answer this question. Summary being 'Wifi' and 'AC' are the most common types of amenities found while it was surprising to see 'workspaces' in the top 15 amenities list.
* Q.4 Predict whether the Airbnb is expensive (> USD 150) or not and what the most important factors that affect the price of an Airbnb? <br/>
  -- Train a GradientBoostingClassifier to answer this particular question and can be seen in the notebook. <br/>
  
You can also read the Medium article for in depth analysis.

### 5. Acknowledgements and additional info

Data source: http://insideairbnb.com/get-the-data.html <br/>
Medium article related to this project: https://medium.com/@malavhirenshah/decoding-data-without-using-machine-learning-well-almost-bbc6ccb32c67

