# CardioGood Fitness---EDA
The market research team at AdRight is assigned the task to identify the profile of the typical customer for each treadmill product offered by CardioGood Fitness. The market research team decides to investigate whether there are differences across the product lines with respect to customer characteristics. The team decides to collect data on individuals who purchased a treadmill at a CardioGoodFitness retail store during the prior three months. The data are stored in the CardioGoodFitness.csv file. The team identifies the following customer variables to study: product purchased, TM195, TM498, or TM798; gender; age, in years;education, in years; relationship status, single or partnered; annual household income ($); average number of times the customer plans to use the treadmill each week; average number of miles the customer expects to walk/run each week; and self-rated fitness on an 1-to-5 scale, where 1 is poor shape and 5 is excellent shape. Perform descriptive analytics to create a customer profile for each CardioGood Fitness treadmill product line.


# Dataset
The Dataset for the EDA project has been taken from Kaggle. Please click on the below link to view the same

[CardioGood Fitness](https://www.kaggle.com/saurav9786/cardiogoodfitness/ "CardioGood Fitness")

# Features
  - Product - the model no. of the treadmill
  - Age - in no of years, of the customer
  - Gender - of the customer
  - Education - in no. of years, of the customer
  - Marital Status - of the customer
  - Usage - Avg. # times the customer wants to use the treadmill every week
  - Fitness - Self rated fitness score of the customer (5 - very fit, 1 - very unfit)
  - Income - of the customer
  - Miles- expected to run

# Objective
  - Come up with a customer profile (characteristics of a customer) of the different products
  - Based on the data we have to generate a set of insights and recommendations that will help the company in targetting new customers

# Questions to be answered
  - How many models does store have?
  - Which is most sold Model?
  - Are Male customers buying treadmill more than female customers?
  - What is the Income ,Age , Education of people buying treadmill?
  - How many days and miles customer expect to run on treadmill?
  - What is the self rated fitness of customers buying treadmill?
  - Are married customer buying Treadmill more than Single customers?
  - Is there any relation between Income and model?
  - Is there any relation between Age and model?
  - Is there any relation between self rated fitness and model?
  - Is there any relation between education and model.?
  - Does gender has any effect on model customer buy?
  - Does Martial status has any effect model customer buy?
  - Is there different age groups buying different models?
  - Relation between Age, Income and education and model bought?


# Exploratory Data Analysis
# 1. Univariate Analysis

- Income is skewed towards right , Median is 50K , Mean is 55k and mode is $45K. Most of the customers are in lower pay range and earn less than 70K. Income has some outliers. Few customers earn beyond 80K.

![image](https://raw.githubusercontent.com/PeyalBhattacharjee/Cardio-Good-Fitness---EDA/main/Images/Capture_1.PNG)

- Age is skewed towards right. Customers buying treadmill are younger and average age of customer is 28 , median is 26 and mode is 25. Customers buying treadmill after age of 40 and before 20 are very less.

![image](https://raw.githubusercontent.com/PeyalBhattacharjee/Cardio-Good-Fitness---EDA/main/Images/Capture_2.PNG)

- Miles is skewed towards right. Customers expect to run on an average 80 miles per week. There are some outliers, where customers are expecting to run more than 200 miles per week.

![image](https://raw.githubusercontent.com/PeyalBhattacharjee/Cardio-Good-Fitness---EDA/main/Images/Capture_3.PNG)

- Most of the customers have self-rated their fitness as 3(average).

![image](https://raw.githubusercontent.com/PeyalBhattacharjee/Cardio-Good-Fitness---EDA/main/Images/Capture_4.PNG)

- 44.4% customers brought TM195. TM195 model is the most purchased model. TM498 was purchased more than TM798. 57.8% male brought Treadmill.There are more Male customers than Female customers. 59.4% of the customers who purchased treadmill are Married.

![image](https://raw.githubusercontent.com/PeyalBhattacharjee/Cardio-Good-Fitness---EDA/main/Images/Capture_5.PNG)

# 2. Bivariate Analysis

- TM195 model was equally bought my Male and Female. Compared to females, male bought TM498 model. TM798 model is popular in Males than in female.

![image](https://raw.githubusercontent.com/PeyalBhattacharjee/Cardio-Good-Fitness---EDA/main/Images/Capture_6.PNG)

- Age and Income has some in significant correlation. Education and Income has very little correlation. There is some corelation between Usage and Income. Fitness and miles are corelated. TM798 model is correlated to Education, Usage,Fitness, Income and Miles. Miles and usage are positively correlated.

![image](https://raw.githubusercontent.com/PeyalBhattacharjee/Cardio-Good-Fitness---EDA/main/Images/Capture_7.PNG)

- There are many outliers for TM798 ,customers are more than age of 40. Age of customers buying TM195 and TM498 is between 20-35, where as customers buying TM798 are primarily in 25-30. Customers with higher income and more education have purchased TM798 model. Customers with lower income purchase TM195 and TM498 model may be because of cost of the Treadmill. Customer with TM 195 expect to use treadmill 3-4 times a week and have average self rated fitness as 3 and some unfits. Customers who bought TM498 model expecting to use Treadmill less frequently but to run more miles a week. Customer buying TM798 plan to use it more frequently , run more miles and have high self rated fitness .They seem to be more health conscious or professionals. TM 798 model was purchased more by males customer than female customers. More partnered customer tend to buy TM798 than Single customers.

![image](https://raw.githubusercontent.com/PeyalBhattacharjee/Cardio-Good-Fitness---EDA/main/Images/Capture_8.PNG)
![image](https://raw.githubusercontent.com/PeyalBhattacharjee/Cardio-Good-Fitness---EDA/main/Images/Capture_9.PNG)
