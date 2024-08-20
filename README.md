# Customer Coupon Analysis
This project is an exercise that I completed for my UC-Berkeley Professional Certification in AI and Machine Learning. 

-- Project Status: Completed

## Project Intro/Objective:
The purpose of this project is to analyze various factors that may influence customer acceptance of restaurant coupons delivered while driving through town. Would you accept a coupon and take a short detour to a restaraunt, if presented with the option? 

### Methods Used:
* Inferential Statistics
* Data Visualization

### Technologies:
* Python
* Pandas, jupyter

## Project Description:
The goal of this project was to understand the factors related with customer acceptance of restaurant coupons delivered in differing driving scenarios. The steps involved include:
- data exploration/descriptive statistics
- data processing/cleaning
- brief writeup/reporting

This data comes to us from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios including the destination, current time, weather, passenger, etc., and then ask the person whether he will accept the coupon if he is the driver. Answers that the user will drive there ‘right away’ or ‘later before the coupon expires’ are labeled as ‘Y = 1’ and answers ‘no, I do not want the coupon’ are labeled as ‘Y = 0’. There are five different types of coupons -- less expensive restaurants (under $20), coffee houses, carry out & take away, bar, and more expensive restaurants ($20 - $50).

#### Key findings:
1. Coffee houses were the most frequently recommended, but also represent a pretty even split across acceptance and non-acceptance. Low-cost restaurants and carry out & take away, were the coupons with the highest acceptance rates vs non-acceptance of offer.
2. Customers having less than 1 visits per month to coffee houses led to the lowest acceptance rate, by far, at ~19% acceptance (well below the 57% average). This is in line with the bar coupon acceptance as well - customers that frequent the places that match the coupon they received are most likely to accept the respective coupon.
   
## Getting Started:

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Raw Data is being kept [here](Repo folder containing raw data) within this repo.

    *If using offline data mention that and how they may obtain the data from the froup)*
    
3. Data processing/transformation scripts are being kept [here](Repo folder containing data processing scripts/notebooks)

## Featured Notebooks/Analysis/Deliverables
* [Notebook](link)

