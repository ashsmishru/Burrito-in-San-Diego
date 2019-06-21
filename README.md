# Burrito-in-San-Diego(Analyzing burrito quality)

Burrito in San Diego:
              Mexican cuisine is often the best food option is southern California. And the burrito is the hallmark of delicious taco shop food: tasty, cheap, and filling. Appropriately, an effort was launched to critique burritos across the county and make this data open to the lay burrito consumer. At this time, the data set contains ratings from over 200 burritos from around 50 restaurants. There are 10 core dimensions of the San Diego burrito. 
              * Volume 
              * Tortilla quality 
              *Temperature * Meat quality 
              * Non-meat filling quality 
              * Meat-to-filling ratio * Uniformity 
              * Salsa quality * Flavor synergy 
              * Wrap integrity. 
     All of these measures (except for Volume) are rated on a scale from 0 to 5, 0 being terrible, and 5 being optimal. Other information available for each burrito includes an overall rating, cost, Yelp rating of the restaurant, and more.

Data Analysis Using Machine Learning:
                Machine learning is an application of artificial intelligence (AI) that provides systems the ability to automatically learn and improve from experience without being explicitly programmed. Machine learning focuses on the development of computer programs that can access data and use it learn for themselves.
                The process of learning begins with observations or data, such as examples, direct experience, or instruction, in order to look for patterns in data and make better decisions in the future based on the examples that we provide. The primary aim is to allow the computers learn automatically without human intervention or assistance and adjust actions accordingly.

Types of machine learning
        -- Supervised Learning
        -- Unsupervised Learning
        -- Reinforcement Learning

Supervised learning:
            It is a type of training the computer with few percent of a set of known input datas and known output datas then after making the computer trained we can predict the unkown outcome of an wanted input data. It includes Classification type and regression type of data solving
            It includes Linear, Logistic regression, Support Vector Machines,naive Bayes, decision trees, k-nearest neighbor algorithm.

Steps for solving the data analysis usinng machine learning basically involves:

-- We need to import all the Libraries which is necessary for analysis.

1)numpy which is the numperical python it includes all scientific calculation and storing multidimension array etc.
2)Pandas, a convenient library that supports dataframes . Pandas is technically optional because Scikit-Learn can handle numerical matrices directly, but it'll make analysis easier
3)train_test_split() function from the model_selection module. As its name implies, this module contains many utilities that will help us choose between models. where the data wil be split into training datas nd few as testing datas
4)preprocessing module contains utilities for scaling, transforming, and wrangling data.

-- Load data.

--Split data into training and test sets.

--Declare data preprocessing steps.

--Evaluate model on test data

The datasheet taken for analysis is Burrito in SanDiego where we need to analysis maily three conditions these analysis is done based on considering mainly by 10 dimensions i.e 'Volume', 'Tortilla', 'Temp', 'Meat', 'Fillings','Meat:filling', 'Uniformity', 'Salsa', 'Synergy', 'Wrap' analysis involves:

1)Identify the best and worst burritos in San Diego  
2)Characterize the variance in burrito qualities across the county.
3)Generate models for what makes a burrito great and investigate correlations in its dimensions


Further analysis also include
analysis done in burrito in san diego(part 3)

1)Descriptive statistics
2)Taco shop ranking
3)Modeling of overall satisfaction as a function of individual burrito dimensions
4)Principal component analysis
5)Difference between across-restaurant variance and within-restaurant variance
Calculating total ratings given to top best to last best restaurants for each dimension and plotting the graph


Few more analysis includes

Number of burritos / restaurants / reviewers in db

1--Lets find total number of burritos, restaurants and reviewers first
2--Lets find total number of each unique value of Taco shop, Burrito, reviewer
3--calculating best resturants based on overall rating
4--Now lets calculate the ratings list given at top  best restaurants
5--Now lets see which are the burritos which are rated at the best at the top resturants 
6--Reviewer who have rated at the best taco shops at a high ratings
7--Now lets calculate the ratings list given at top least best restaurants

Number of different burritos rated at Taco Stand

Number and average ratings for each reviewer, sorted by most ratings

Finding the average ratings of each dimensions at top best restaurants to least best restaurants (i.e) keeping dimensions common varying the restaurants ??

Finding the average ratings of different dimensions at top best restaurants to least best restaurant(i.e) keeping restaurant common we shall find average of different demension??

Calculating the total no. of Burritos accordingly to the cost

Only California burritos from Taco Stand

Overall ratings when Meat rating was 2.5 or lower

Taco shops with average salsa rating >=4, and number of ratings

Taco shops with free chips, and average overall rating

Taco shops with yelp rating >=4 stars, with average burrito rating

Average ratings of each taco shop in each dimension

Calculating total ratings given to top best to last best restaurants for each dimension and plotting the graph

Taking the maximum count of the rating of each dimension from top best to last best tacoshops
analysis seen in Burrito in San Diego(part 6)

Information on the project can be obtained through following links
https://srcole.github.io/100burritos/

https://www.kaggle.com/srcole/burritos-in-san-diego

https://github.com/srcole/burritos

https://docs.google.com/presentation/d/1jBm4GFYtNnwSkALODX2CwXRmHQmVDrRoeF8cSG8tnDY/edit#slide=id.g2d390cd055_0_96

