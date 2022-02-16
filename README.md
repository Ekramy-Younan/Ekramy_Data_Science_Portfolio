# Ekramy_Data_Science_Portfolio
Data Science Projects

# [Project: Natural Learning Processing - using DecisionTreeClassifier]
 * I used Congenital_disorders and Infectious_diseases from the Wikipedia folder.
 * The following metrics table for the max features in [1,5,10,50,100,500] and max_depth in [3 & 2].
 * ![image](https://user-images.githubusercontent.com/76533174/154201106-e25da8c8-f807-405c-830c-791a5680a0e6.png)
 * ![image](https://user-images.githubusercontent.com/76533174/154201125-ba9ee8a5-9715-408f-9ae7-13c2d831b7d1.png)

# [Project: Predicting Loan Defaults using Deep Learning with Keras & Tensorflow](https://github.com/Ekramy-Younan/Lending-Club-Loan)
Problem Statement:
For companies like Lending Club, predicting loan default with high accuracy is very important. Using the historical Lending Club data from 2007 to 2015, build a deep learning model to predict the chance of default for future loans.

Analysis to be done:
Perform data preprocessing, exploratory data analysis, and feature engineering. Build a deep learning model to predict load default using the historical public data (https://www.lendingcub.com).

Dataset:
The data set used here can be downloaded from here. The CSV file contains complete loan data for all loans issued through 2007–2015, including the current loan status and payment information. Additional features include annual income, public records, revolving balance, and others.

![](/Images/Lending_Club_Loan_Correlation.png)

We only focus on the grids of yellow or very light green. After comparing with the feature description again, I decided to drop:’revol.bal’, ‘days.with.cr.line’, ‘installment’, ‘revol.bal’ revol.bal, day.with.cr.line, installment can represent by annual income. revol.util can represent by int.rate.


# [Project: Income-Qualification](https://github.com/Ekramy-Younan/Income-Qualification)

**DESCRIPTION
  * Identify the level of income qualification needed for the families in Latin America.

**Problem Statement Scenario:
  * Many social programs have a hard time ensuring that the right people are given enough aid. It’s tricky when a program focuses on the poorest segment of the population. This segment of the population can’t provide the necessary income and expense records to prove that they qualify.
  * In Latin America, a popular method called Proxy Means Test (PMT) uses an algorithm to verify income qualification. With PMT, agencies use a model that considers a family’s observable household attributes like the material of their walls and ceiling or the assets found in their homes to classify them and predict their level of need.
  * While this is an improvement, accuracy remains a problem as the region’s population grows and poverty declines.
  * The Inter-American Development Bank (IDB)believes that new methods beyond traditional econometrics, based on a dataset of Costa Rican household characteristics, might help improve PMT’s performance.

![](/Images/Income_Qualification_Correlation.png)

Create correlation matrix
Select upper triangle of correlation matrix
Find index of feature columns with correlation greater than 0.95


# [Project: Mercedes-Benz-Greener-Manufacturing](https://github.com/Ekramy-Younan/Mercedes-Benz-Greener-Manufacturing)
**Description:

Reduce the time a Mercedes-Benz spends on the test bench.

**Problem Statement Scenario:

"Since the first automobile, the Benz Patent Motor Car in 1886, Mercedes-Benz has stood for important automotive innovations. These include the passenger safety cell with a crumple zone, the airbag, and intelligent assistance systems. 
Mercedes-Benz applies for nearly 2000 patents per year, making the brand the European leader among premium carmakers. Mercedes-Benz is the leader in the premium car industry. With a huge selection of features and options, customers can choose the customized Mercedes-Benz of their dreams. 
To ensure the safety and reliability of every unique car configuration before they hit the road, the company’s engineers have developed a robust testing system. As one of the world’s biggest manufacturers of premium cars, safety and efficiency are paramount on Mercedes-Benz’s production lines. 
However, optimizing the speed of their testing system for many possible feature combinations is complex and time-consuming without a powerful algorithmic approach. You are required to reduce the time that cars spend on the test bench. 
Others will work with a dataset representing different permutations of features in a Mercedes-Benz car to predict the time it takes to pass testing. Optimal algorithms will contribute to faster testing, resulting in lower carbon dioxide emissions without reducing Mercedes-Benz’s standards."

![](/Images/Mercedes_Change_in_target_value.png)

There doesn't seem to be anything overly suspicious here - looks like a random sort.


# [Project: Uber-Fare-Prediction](https://github.com/Ekramy-Younan/Uber-Fare-Prediction)

**Description:

Design an algorithm which will tell the fare to be charged for a passenger.

**Problem Statement Scenario:

A fare calculator helps a customer in identifying the fare valid for the trip. They are often used by passengers who are new to a city or tourists to get an estimate of travel costs. You are provided with a dataset with features like fare amount, pickup and drop location, passenger count, and so on.

![](/Images/Uber_fare_prediction_fare_amount.png)

In distribution plot also it can be seen that there are some values which are negative fare.


# [Project: Amazon-Employee-Access](https://github.com/Ekramy-Younan/Amazon.com---Employee-Access)

**Description:

Design an algorithm to accurately predict the access status to certain resources of employees

**Problem Statement Scenario:

When employees start working at an organization, they first need to obtain the computer access necessary to fulfil their role. This access may allow employees to read/manipulate resources through various applications or web portals.  
It is assumed that employees fulfilling the functions of a given role will access the same or similar resources. Often, employees figure out the access they need as they encounter roadblocks during their daily work (such as, not being able to log into a reporting portal). 
A knowledgeable supervisor then takes time to manually grant the access needed to overcome the obstacles. As employees change roles within a company, this access discovery/recovery cycle wastes a non-trivial amount of time and money. 
There is a considerable amount of data regarding employees’ roles within an organization and the resources to which they have access. Given the data related to current employees and their provisioned access, models can be built that automatically determine access privileges as employees enter and leave roles within a company. 
These auto-access models seek to minimize the human involvement required to grant or revoke employee access.

![](/Images/amazon_access_Action.png)

