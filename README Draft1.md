<div align = "center">
 
 # Investment Survey

 </div>
 <br>
 <div align = "center">
  
## Investment_Survey project description & summary

</div>

<img src="https://github.com/Erasmus125/Investment-Survey/blob/787cddf7d039395f21cc57efc066a4a08a86acdc/Images%20ReadMe/HeaderImage.jpg" width="1000" height="500">
Investors play a crucial role in the economy by facilitating wealth creation, funding businesses, and contributing to financial stability and growth.  Investors are integral to economic growth, financial security, and community development. By understanding the importance of investing, individuals can make informed decisions that enhance their financial futures and contribute to the overall health of the economy

[Search: Why are investors important](https://www.bing.com/search?q=why+are+investors+important&form=ANNTH1&refig=693c67466d5f49a9a7124e4d56428715&pc=LCTS&pq=why+are+invest&pqlth=14&assgl=27&sgcn=why+are+investors+important&qs=UT&sgtpv=UT&smvpcn=0&swbcn=10&sctcn=0&sc=10-14&sp=2&ghc=0&cvid=693c67466d5f49a9a7124e4d56428715&clckatsg=1&hsmssg=0)

This project is a data-driven analysis that uses multiple tools to explore the motivations that impel people to invest, how they invest and on what they invest.

###	 1) What is the project about?
In this project (the end-part of another assignment to learn about Cloud Azure) I explore and analyze the results of a survey done on a 100 people about their investment practices.
### About the DataSet.
The [original Investment Survey data](https://github.com/Erasmus125/Investment-Survey/blob/a86066a7a52772fe0896c34b9adacd29365a6a8a/investment_survey_csv.csv) was taken from [Kaggle](https://www.kaggle.com/datasets/sudarsan27/investment-survey-dataset).

The dataset has no pretensions to being of world-wide relevance or of being statistically valid.  Little is known about the methodology: the survey instrument, on whom it was applied, how the population was selected, etc.  There is some ambiguity about what some of the variables, and what some of the categories mean actually mean e.g. Working/Professional.  Having access to the methodology would have been helpful in assessing the relevance of the data analysis.

For the purpose of this project, we will take the findings as being relevant to a general population and of use to financial institutions or to any institution interested in getting people to invest.

Furthermore, for money variables, the currency is taken to be in American dollars ($).

#### **Table 1:  Investment Survey dataset before Recoding**<br>
There were 10 variables in this dataset, and the number of respondents was 100.

<details open><summary><strong>Click to hide</strong></summary>
 
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

</details>

  ### **Technology used.**
  * Power BI to clean and transform data, analyze gender differences and create an interactive dashboard.
  * Excel to analyze to clean and transform data, analyze differences between the dichotomizedWorking/Professional variable and create an interactive dashboard.
  * SQL queries to get means.
  * Jupyter and Colab Python – further exploration.

### **2)	Why this project matters**
The goal was to inform media and investment companies on how to effectively target potential investors based on demographics such as gender and employment status AND to understand what drives people to invest.

### 3)	Major findings.
Major findings of this project included that women are more cautious investors than men:  women are significantly more likely than men to invest in stable institutions such as banks and in precious materials such as gold.  This should help financial institutions market their portfolios accordingly.  There are also significant differences on what pushes men and women to invest:  personal savings being a primary incentive for women, and wealth generation for men.

Women are more likely to be motivated by family to invest, whereas men are more likely to be motivated by social media and friends.  Family is a major source of investment advice for both men and women, but men are significantly more likely than women to use mobile applications and news articles or current affairs as resources for investment.  These findings can guide financial institutions on how to reach out to potential investors.
<div align="center">

 ### Power BI for an exploration of Gender differences.

 </div>

The following
[PowerBI dashboard](https://github.com/Erasmus125/Investment-Survey/blob/8bb57ea4c2294b5049189cd8411b4b42153eeec2/InvestmentSurveycsv.pbix) can be used to explore differences by other variables as well, but I shall focus on the differences between the genders when it comes to investment practices.
Link to PowerBI
But I’m only giving differences between genders here.
In PowerBI, I categorized the following variables for ease of understanding.
I first created the measure, and then the label.
<br>
 
#### **Table 2:  PowerBI Recode**
<details open>
<summary><strong>Click to hide</strong></summary>

<img width="857" height="632" alt="image" src="https://github.com/user-attachments/assets/d252c64d-6ded-427b-a08b-a94197266e5a" />
<img width="899" height="645" alt="image" src="https://github.com/user-attachments/assets/e5e9a60f-9960-49f0-ad6a-ca555f56a03b" />
<img width="899" height="645" alt="image" src="https://github.com/user-attachments/assets/5f4ef8aa-3b4f-487e-9523-08e098c1bd41" /> 
<br/><br/>

</details>

<div align ="center">
 
## **PowerBI**

</div>

#### **Charts 1:  Gender Differences in Investment**
<details open>
<summary><strong>Click to hide</summary></strong>
 
<img width="902" height="542" alt="image" src="https://github.com/user-attachments/assets/f94030ac-6976-4c94-93c6-627995916e46" /> <br>
<img width="900" height="503" alt="image" src="https://github.com/user-attachments/assets/7bbed6a1-80e0-4212-acec-4ad9c929b13c" />

</details>
 
 #### **Table 3: Highlights of Differences between Gender in Investment**

<details open>
<summary><strong>Click to hide</strong></summary>
<img width="899" height="629" alt="image" src="https://github.com/user-attachments/assets/23ab716a-cbf8-434a-9b4f-92485edcbd96" />

</details>

<div align = "center">

### **Excel for an Exploration of Investment differences amongst Working Professional/Not Working.**

</div>
The Excel part of this project is focusing on the differences in investment between those who are not working and those who are Working/Professional.

Recodes were done using a mixture of Nested IF, IFS.

#### **Table 4: Excel Recode**
<img width="992" height="664" alt="image" src="https://github.com/user-attachments/assets/120e8cb8-02c4-4340-9781-d9e260a41b41" />
<img width="991" height="387" alt="image" src="https://github.com/user-attachments/assets/4f65003f-857a-41f5-80a3-b2cb49875ca1" /> <br>
<br>

**Chart 3: [Excel Dashboard](https://github.com/Erasmus125/Investment-Survey/blob/b77a7c5c3996770f875d01ae94fa2b8d45e2eceb/Investment_survey_ExcelDashboard.xlsx)**<br>

<details open>
<summary><strong>Click to hide</summary></strong>

<img width="1125" height="562" alt="image" src="https://github.com/user-attachments/assets/222eb7c4-2e97-4a5a-80d6-314cdd57f2b5" /> <br>
<br>

</details>

**Table 4:  Highlights from Comparison of Investment differences between Working/Professional and Non-Working respondents.**<br>

<details open>
 
<summary><strong>Click to hide</summary></strong>
 
<img width="1030" height="682" alt="image" src="https://github.com/user-attachments/assets/f6191d83-6237-4c28-9ed5-9b19ef20c0aa" />

</details>

<details>
  <summary><strong>Click to expand</strong></summary>

  Content goes here.
  You can include text, lists, code blocks, images, etc.

</details><br>

<div align = "center">

### **SQL Exploration of Selected Variables and Values by Employment and Gender**<br>

</div>

The previous analysis of Investment practices by Gender and by Work/Professional status indicated a further exploration of certain values might be worthwhile.

We looked at the influence of Gender alone and Working/Professional status alone, although both dashboard in PowerBI and Excel allow us to drill down further.

I will use SQL to combine the variables of Gender and Employment to look more closely on how Gender and Employment status combined influence selected values in certain variables.  The values selected were influenced by major differences between the genders or major differences between the working and not-working showing up in the visuals. 

#### **Methodology**<br>

The [Investment Survey file](https://github.com/Erasmus125/Investment-Survey/blob/070970373037863ba0b54a5eab106fe8c93a42d0/InvestSurveySQL.xlsx) was uploaded to SQL .  

The only changes made, prior to uploading to SQL, was that four “Nill” values affecting three records of the one hundred records were converted to 0.  

While uploading to MySQL Workbench 8.0 CE, variables such as Age, Annual Income, Investment_per_month and Duration_to_save were converted from Text format to Number format.
The following variables were renamed, and the following variables categorized.

#### **Table 5:  SQL Coding**
<details>
<summary><strong>Click to hide</strong></summary>
 
<img width="884" height="565" alt="image" src="https://github.com/user-attachments/assets/409fbcc2-d97b-4a19-90f9-5e01b20b7bbe" />
<img width="884" height="112" alt="image" src="https://github.com/user-attachments/assets/7615fb3a-d09c-4b7d-8e81-35174ab24ae3" />
<img width="888" height="397" alt="image" src="https://github.com/user-attachments/assets/f5d93473-8f63-4d5d-87ba-72decdd29307" />

</details><br>

Since the focus was on selected values within a variable, the number of respondents were very small, ranging from 12 to 48.  The totals would sometimes add up to just over 100% due to rounding-off.
#### **Investment Goal**
**Personal Savings** (n=26):  Irrespective of gender, 70 % of those not-working compared to 31% (rounding off error) of those working had personal savings as their invest goal.
**Wealth Generation** (n=28):  Working males (46%) and non-working males (21%) were far more likely than females to have wealth generation as their goal.
#### **Investment Mode**
**Stocks** (n=29):  In this group, stock investors were overwhelmingly male with 48% working and 41% not working.
23 of the 26 respondents who invested in **mutual funds** were working people of both genders.
**Banking** (n=23):  69% (16) of those who invested in banks were not working compared to the remaining 31% (7) who were not-working.
#### **Motivation**
**Family members**(n=24):  Females were far more likely (80%), irrespective of working status to be motivated by family members to invest compared to 21% of male respondents.  
However, when it came to motivated by **friends**, 21 of the 24 respondents were males.  
Of the 18 who said they used **Social media/Articles**, 15 were males. 
#### **Resources Used**
**Family members/Friends** (n=48) were a resource used for investments almost equally by both genders: 50% of males (29% working vs. 21% not working) compared to 50% of females (equally divided between working and not working).  
Of the 12 respondents who used **News articles /Current affairs** as an investment resource, all were males.<br>

<div align ="center">
 
## **What I learned.**

</div>
I learned about GitHub in the process, how to navigate within it on a very elementary level.  I was very proud of being able to rename my file, create branches, add and delete files. 

I also found out what a data scientist’s portfolio should look like.  In my ignorance, I thought, all I have to do is shove my project there somehow, and, since it’s all about coding, people will look at the code for proof that I know something.  Now I can navigate on a very basic level in Git Hub and I know what a ReadMe is about and what it can do.

Thanks to GitHub ReadMe, I was introduced to HTML and Markup Language – something I had never done before.

**Major Challenges.**  
o	Creating measures I needed in Power BI using DAX within time constraints.  Not used to using PowerBI to create categories.<br>
o	Getting the following pop-up in PowerBI **everytime** I clicked anywhere on PowerBI, so my work was doubled.
<img width="400" height="200" alt="image" src="https://github.com/user-attachments/assets/5ea8823f-bde5-4bbc-b224-69f73d2c236b" /><br>
o	Losing all my Excel work for SQL and having to start all over again.  But I was thankful I’d commented on my work in SQL, because that made things a LOT easier.



