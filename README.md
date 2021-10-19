# PREDICTED CHURN RATE OF CREDIT CARD BY FINANCIAL HABITS
Data Analyze, and Predict Churn Rate by Using Random Forest
## 1. Problem Statment:
A manager at the bank is disturbed with more and more customers leaving their credit card services. They would really appreciate if one could predict for them who is gonna get churned so they can proactively go to the customer to provide them better services and turn customers' decisions in the opposite direction.

I got this dataset from a website with the URL as https://leaps.analyttica.com/home. I have been using this for a while to get datasets and accordingly work on them to produce fruitful results.

Now, this dataset consists of 10,000 customers mentioning their age, salary, marital_status, credit card limit, credit card category, etc. There are nearly 18 features.

Datasource: https://www.kaggle.com/sakshigoyal7/credit-card-customers

## 2. Data Information:

**CLIENTNUM** : Client number. Unique identifier for the customer holding the account <br>
**Attrition_Flag** : Internal event (customer activity) variable - if the account is closed then 1 else 0 <br>
**Customer_Age:** Demographic variable - Customer's Age in Years<br>
**Gender:** Demographic variable - M=Male, F=Female<br>
**Dependent_count:** Demographic variable - Number of dependents<br>
**Education_Level:** Demographic variable - Educational Qualification of the account holder (example: high school, college graduate, etc.)<br>
**Marital_Status:** Demographic variable - Married, Single, Divorced, Unknown<br>
**Income_Category:** Demographic variable - Annual Income Category of the account holder (< 40K, 40K - 60K, 60K - 80K, 80K-120K, > 120K, Unknown) <br>
**Card_Category:** Product Variable - Type of Card (Blue, Silver, Gold, Platinum) <br>
**Months_on_book:** Period of relationship with bank<br>
**Total_Relationship_Count:** Total no. of products held by the customer <br>
**Months_Inactive_12_mon:** No. of months inactive in the last 12 months <br>
**Contacts_Count_12_mon:** No. of Contacts in the last 12 months <br>
**Credit_Limit:** Credit Limit on the Credit Card <br>
**Total_Revolving_Bal:** Total Revolving Balance on the Credit Card <br>
**Avg_Open_To_Buy:** Open to Buy Credit Line (Average of last 12 months) <br>
**Total_Amt_Chng_Q4_Q1:** Change in Transaction Amount (Q4 over Q1) <br>
**Total_Trans_Amt:** Total Transaction Amount (Last 12 months) <br>
**Total_Trans_Ct:** Total Transaction Count (Last 12 months) <br>
**Total_Ct_Chng_Q4_Q1:** Change in Transaction Count (Q4 over Q1) <br>
**Avg_Utilization_Ratio:** Average Card Utilization Ratio. <br>

## 3. Work Content:
<h3>Table of contents</h3>
<div class="alert alert-success" style="margin-top:15px">
    <u
       <li><font color='blue'>Module 1: Import Library and Dataset</li><br>
    <u
       <li>Module 2: Data Cleaning</li><br>
    <u
       <li>Module 3: Data Wrangling</li><br>
    <u
       <li>Module 4: EDA - Exploratory Data Analysis</li>
                <li><font color='black'>1. Demographic Analysis</li>
                <li><font color='black'>2. Credit Products Analysis</li>
    <uI. 
       <li>Module 5: Model Development</li>
                <li><font color='black'>1. Preprocessing</li>
                <li><font color='black'>2. Train-Test Splitting</li>
                <li><font color='black'>3. Using SMOTE to upscale training set</li>
                <li><font color='black'>4. Evaluation again with SMOTE</li>
            </ol>
    </ul>
</div>
<hr>
