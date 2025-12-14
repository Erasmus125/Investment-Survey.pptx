<div align = "center">
 
 # Investment Survey

 </div>
Investment_Survey project description & summary

<img src="https://github.com/Erasmus125/Investment-Survey/blob/787cddf7d039395f21cc57efc066a4a08a86acdc/Images%20ReadMe/HeaderImage.jpg" width="1000" height="500">
Investors play a crucial role in the economy by facilitating wealth creation, funding businesses, and contributing to financial stability and growth.  Investors are integral to economic growth, financial security, and community development. By understanding the importance of investing, individuals can make informed decisions that enhance their financial futures and contribute to the overall health of the economy 
(adapted from why are investors important - Search: https://www.bing.com/search?q=why+are+investors+important&form=ANNTH1&refig=693c67466d5f49a9a7124e4d56428715&pc=LCTS&pq=why+are+invest&pqlth=14&assgl=27&sgcn=why+are+investors+important&qs=UT&sgtpv=UT&smvpcn=0&swbcn=10&sctcn=0&sc=10-14&sp=2&ghc=0&cvid=693c67466d5f49a9a7124e4d56428715&clckatsg=1&hsmssg=0
This project is a data-driven analysis that uses multiple tools to explore the motivations that impel people to invest, how they invest and on what they invest.

###	 1) What is the project about?
In this project (the end-part of another assignment to learn about Cloud Azure) I explore and analyze the results of a survey done on a 100 people about their investment practices.
### About the DataSet.
The [original Investment Survey data] (https://github.com/Erasmus125/Investment-Survey/blob/a86066a7a52772fe0896c34b9adacd29365a6a8a/investment_survey_csv.csv) was taken from Kaggle:  https://www.kaggle.com/datasets/sudarsan27/investment-survey-dataset

The dataset has no pretensions to being of world-wide relevance or of being statistically valid.  Little is known about the methodology: the survey instrument, on whom it was applied, how the population was selected, etc.  There is some ambiguity about what some of the variables, and what some of the categories mean actually mean e.g. Working/Professional.  Having access to the methodology would have been helpful in assessing the relevance of the data analysis.

For the purpose of this project, we will take the findings as being relevant to a general population and of use to financial institutions or to any institution interested in getting people to invest.

Furthermore, for money variables, the currency is taken to be in American dollars ($).

There were 10 variables in this dataset, and the number of respondents was 100.
|Variable|Categories (before recoding)|
|---------------------------------------|-----------------------------------------|
|Gender                                 |Male, Female                             |
|Age                                   |Range:  18 years -56 years                |
|Working Professional                  |0,1                                       |
|Annual Income                         |0 (40%) - $600,000                        |
|Mode_of_investment                    |Banking, Stocks, Mutual Funds, Crypto currency, Not prepared , Gold/Other Materials, Marketing , Real estate, Bonds, Chit fund        |
|Investment_per_month                  |$0 - $30,000                              |
Motivation_cause                       |Family member, Social media/ Articles, Agents/Investment brokers, Self Interest , No one, Friends, Self, Through Bank, Self motivation , Self , Schemes|
|Resources_used                        |Family members/Friends, Mobile applications, News articles / Current affairs, Books, Social media/ Articles, Brokers, Investors in bank|
|Goal for investment                   |Family member, Social media/ Articles, Agents/Investment brokers, Self Interest , No one, Friends, Self, Through Bank, Self motivation , Self , Schemes|
|Duration_to_save (in_Years)            |0 years – 25 years.|

### Technology used.
  * Power BI to clean and transform data, analyze gender differences and create an interactive dashboard.
  * Excel to analyze to clean and transform data, analyze differences between the dichotomizedWorking/Professional variable and create an interactive dashboard.
  * SQL queries to get means.
  * Jupyter and Colab Python – further exploration.

### 2)	Why this project matters
The goal was to inform media and investment companies on how to effectively target potential investors based on demographics such as gender and employment status AND to understand what drives people to invest.

### 3)	Major findings.
Major findings of this project included that women are more cautious investors than men:  women are significantly more likely than men to invest in stable institutions such as banks and in precious materials such as gold.  This should help financial institutions market their portfolios accordingly.  There are also significant differences on what pushes men and women to invest:  personal savings being a primary incentive for women, and wealth generation for men.

Women are more likely to be motivated by family to invest, whereas men are more likely to be motivated by social media and friends.  Family is a major source of investment advice for both men and women, but men are significantly more likely than women to use mobile applications and news articles or current affairs as resources for investment.  These findings can guide financial institutions on how to reach out to potential investors.
<div align="center">

 ### Power BI for an exploration of Gender differences.

 </div>
The following Power BI dashboard can be used to explore differences by other variables as well, but I shall focus on the differences between the genders when it comes to investment practices.
Link to PowerBI
But I’m only giving differences between genders here.
In PowerBI, I categorized the following variables for ease of understanding.
I first created the measure, and then the label.

<img width="857" height="632" alt="image" src="https://github.com/user-attachments/assets/d252c64d-6ded-427b-a08b-a94197266e5a" />
<img width="899" height="645" alt="image" src="https://github.com/user-attachments/assets/e5e9a60f-9960-49f0-ad6a-ca555f56a03b" />
<img width="899" height="645" alt="image" src="https://github.com/user-attachments/assets/5f4ef8aa-3b4f-487e-9523-08e098c1bd41" /> 
<br/><br/>
<div align ="center">
 
### **By Gender**

</div>

<img width="902" height="542" alt="image" src="https://github.com/user-attachments/assets/f94030ac-6976-4c94-93c6-627995916e46" /> <br>
<img width="900" height="503" alt="image" src="https://github.com/user-attachments/assets/7bbed6a1-80e0-4212-acec-4ad9c929b13c" />

<div align ="center">
 
### **Gender differences in Investment**

</div>

<img width="899" height="629" alt="image" src="https://github.com/user-attachments/assets/23ab716a-cbf8-434a-9b4f-92485edcbd96" />



