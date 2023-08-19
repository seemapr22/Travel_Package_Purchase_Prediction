# Travel Package Purchase Prediction

## Table of contents

* Libraries
* Read and Understand Data
* Data Preprocessing
* Exploratory Data Analysis
  * Univariate Analysis
  * Bivariate Analysis
* Insights based on EDA
* Model Building-Ensemble Technique
  * Random Forest
  * Gradient Boosting
  * Adaboost
* Conclusion

## Dataset Introduction

**Customer details:**

* **CustomerID:** Unique customer ID
* **ProdTaken:** Whether the customer has purchased a package or not
* **Age:** Age of customer
* **TypeofContact:** How customer was contacted (Company Invited or Self Inquiry)
* **CityTier:** City tier depends on the development of a city, population, facilities, and living standards. The categories are ordered i.e. Tier 1 > Tier 2 > Tier 3
* **Occupation:** Occupation of customer
* **Gender:** Gender of customer
* **NumberOfPersonVisiting:** Total number of persons planning to take the trip with the customer
* **PreferredPropertyStar:** Preferred hotel property rating by customer
* **MaritalStatus:** Marital status of customer
* **NumberOfTrips:** Average number of trips in a year by customer
* **Passport:** The customer has a passport or not
* **OwnCar:** Whether the customers own a car or not
* **NumberOfChildrenVisiting:** Total number of children with age less than 5 planning to take the trip with the customer
* **Designation:** Designation of the customer in the current organization
* **MonthlyIncome:** Gross monthly income of the customer


**Customer interaction data:**

* **PitchSatisfactionScore:** Sales pitch satisfaction score
* **ProductPitched:** Product pitched by the salesperson
* **NumberOfFollowups:** Total number of follow-ups has been done by the salesperson after the sales pitch
* **DurationOfPitch:** Duration of the pitch by a salesperson to the customer

## Objective of the Project

* To predict which customer is more likely to purchase the newly introduced travel package
* Which variables are most significant.
* Which segment of customers should be targeted more.

## Insights based on EDA

| Name    |Basic        |Delux     |King       |Standard       |Super Delux      |
|---------|-----------|----------|------------|---------------|-----|
| Age | 26-30 | 31-40 | 51-70 | 31-40 | 41-50 |
|Monthly Income   | <25000  | <25000 |30000-40000|<30000|25000-35000|
| City Tier | 1  | 3 | 1 or 3 | 3 | 3|
| Marital Status | Single>Married | almost all | mostly all except unmarried | married | mostly single and married |
| Gender | mostly male | mostly male | mostly female | mostly male | moslty male |
| Occupation | mostly salaried>small business>large business | mostly small business | mostly small business | mostly small business and salaried | mostly salaried |
| Designation | Executive | Manager | VP | Senior Manager | AVP |
