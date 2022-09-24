# Ad-Click-Prediction

### MOTIVATION
The main motivation behind the project is “Targeted Advertising”. At its most basic, targeted advertising can just mean that ads are chosen for their relevance to site content, in the assumption that they will then be relevant to the site audience as well. Online advertisers can use different methods to target a particular advertisement on the user based on its traits. Most of company do this as part of social media like Facebook, LinkedIn etc. But most of the times the process goes wrong and the advertisement does not reach its target audience because it is sent out without actually understanding the probability of the occurring click.

### Problem statement
Internet marketing has taken over traditional marketing strategies in the recent past. Companies prefer to advertise their products on websites and social media platforms. However, targeting the right audience is still a challenge in online marketing. Spending millions to display the advertisement to the audience that is not likely to buy your products can be costly.

In this project, we are going to work on an advertising dataset, indicating whether or not a particular internet user has clicked on an Advertisement.

The goal is to predict if a user would click on an advertisement based on the features of the user.
Few assumptions made as a part of this project is: 

1)	User taken into consideration are between the age group of 19 to 61. 
2)	There is almost equal ratio of male and female internet users. 
3)	The ad topic is limited to what is given in the dataset.

### Tech Stack Used:
1. Python
2. Libraries like: Sklearn,pandas,Numpy,matplotlib and seaborn

### Data Set

The dataset consists of below features:

Daily Time Spent on Site: consumer time on site in minutes

Age: Customer age in years

Area Income: Avg. Income of geographical area of consumer

Daily Internet Usage: Avg. minutes a day consumer is on the internet

Ad Topic Line: Headline of the advertisement

City: City of consumer

Male: Whether or not consumer was male

Country: Country of consumer

We have done preliminary EDA(mention below) and we are planning to do more insight as we progress.

### Exploratory Data Analysis 

We came up with some interesting questions on the dataset and we tried to find answers for the same during EDA process.

#### What age group does the dataset majorly consist of? 

We observe that the oldest person in the dataset is 61 years old and the youngest person is 19 years old and the average age as per dataset is 36 years old. We can conclude that the site is targetting adult users.

<img width="616" alt="screen shot 2018-12-06 at 6 08 30 pm" src="https://github.com/Annie-Dhawan/machine-learning-projects/blob/main/Ad-Click-Prediction/AGE_GRP.png">


#### What is the income distribution in different age groups? 

Teenagers are higher earners with age group of 25-35 earning 58k-68k.
We can see that smallest income is dollar 13,996 and the highest is dollar 79,484. This means people are from different social groups. 

<img width="475" alt="screen shot 2018-12-06 at 6 13 34 pm" src="https://github.com/Annie-Dhawan/machine-learning-projects/blob/main/Ad-Click-Prediction/income.png">


#### Which age group is spending maximum time on the internet? 

Age group of 25-40 is most active on the internet. Also we are analyzing a popular website since the time user spend on the website in an average is 65 minutes and min time spent by them is 32 min and max time is 91 min in one seassion. These are huge numbers.


<img width="502" alt="screen shot 2018-12-06 at 6 17 39 pm" src="https://github.com/Annie-Dhawan/machine-learning-projects/blob/main/Ad-Click-Prediction/age%20and%20time%20spent.png">



#### Which gender has clicked more on online ads?

Based on below data we can see that a greater number of females have clicked on ads compared to male.

<img width="261" alt="screen shot 2018-12-06 at 6 19 38 pm" src="https://user-images.githubusercontent.com/22437872/49623712-94f64680-f983-11e8-8572-ac20a0239c4d.png">

#### Correlation: 
1. We can see that there is a positive correatin of Clicked on Ads and age i.e when age increases Clicked on Ads also increases. This means old people     click on ads more.
2. We can see that there is negative correlation between Clicked on Ads and features like- Daily Time Spent on Site,Area Income,Daily Internet Usage.
3. There is no relation of Clicked on Ads and Gender.

<img width="261" alt="screen shot 2018-12-06 at 6 19 38 pm" src="https://github.com/Annie-Dhawan/machine-learning-projects/blob/main/Ad-Click-Prediction/cor.png">

### Models 
The following models(with accuracies) have been used to build this:
1. Logistic Regression (accuracy - 0.97)
2. Naive Bayes (accuracy - 95.75)
3. Random Forest (accuracy - 0.965)
4. Decision Tree (accuracy - 0.94)

### Conclusion 

Comparing all the above implementation models, we conclude that Logistic Regression gives us the maximum accuracy for determining the click  probability. We believe in future there will be fewer ads, but they will be more relevant. And also these ads will cost more and will be worth it. Our model can basically predict if a certain customer will see the ad or not and it will save us huge amount of money as it will tell us before hand only whether to invest on that customer or not.



