## BI Dashboard with AWS QuickSight - Healthcare Analytics
Author: Thanujhaa Sriee (email: thanujhaa.sriee@gmail.com)
<hr height: 5px>

### Project Description:
The Office of Enterprise Data and Analytics, within the Centers for Medicare & Medicaid Services (CMS), has developed a set of information products that examine enrollment activity in the Health Insurance Marketplaces (the Marketplaces).  The Marketplaces were established in 2014 and allow individuals to shop for health insurance and dental plans. This dataset is publicly available and we will make a case study of various insurances available in the market and analyze them rhough the AWS Quick Sights tool and build a story line 

### Goal for this project is to analyze data health insurance data and help understand what type of apps are likely to attract more users.</span>

### Table of Contents
* About dataset
* Exploring the Data
* Most Common Apps by Genre
* Most Popular Apps by Genre on the App Store
* Most Popular Apps by Genre on Google Play
* Conclusion/Findings

### Exploring the Data
As of September 2018, there were approximately 2 million iOS apps available on the App Store, and 2.1 million Android apps on Google Play.

Collecting data for over four million apps requires a significant amount of time and money, so we'll try to analyze an existing sample of data. 

* [A data set](https://www.kaggle.com/lava18/google-play-store-apps) containing ~10K records Android apps from Google Play
* [A data set](https://www.kaggle.com/ramamet4/app-store-apple-data-set-10k-apps) containing ~7K iOS apps from App Store

***STEPS TO LOAD CSV FILE INTO S3***
* Login into your AWS account, From Services console choose S3
![image](https://user-images.githubusercontent.com/69738890/101584095-77a94800-39a2-11eb-8c55-fe8f5d2e263b.png)

* Click on Create Bucket
![image](https://user-images.githubusercontent.com/69738890/101584163-a1fb0580-39a2-11eb-99ca-1fad55dd6752.png)

* Upload File from your local into S3
![image](https://user-images.githubusercontent.com/69738890/101584235-cce55980-39a2-11eb-9fb2-e879bff929ee.png)


![image](https://user-images.githubusercontent.com/69738890/101584298-f69e8080-39a2-11eb-91df-f18062ea0b13.png)

*
![image](https://user-images.githubusercontent.com/69738890/101584384-29487900-39a3-11eb-8b87-9c17275b2aa3.png)

* Change permissions -> edit Block Public access , default access permisions for your files will be private
![image](https://user-images.githubusercontent.com/69738890/101584426-411ffd00-39a3-11eb-94d0-c38e8b0eba9f.png)

* Finally, make your data Public 
![image](https://user-images.githubusercontent.com/69738890/101584543-8fcd9700-39a3-11eb-9303-c9f0e15aa484.png)






