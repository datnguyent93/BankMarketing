## Bank Marketing Dataset Analysis

---

### Background:

The **Bank Marketing Dataset**, sourced from Kaggle and UCI, details the outcomes of telemarketing campaigns for term deposits from 2008 to 2013. It includes client demographics, financial details, and interactions with the campaign.
([Source: Kaggle](https://www.kaggle.com/datasets/janiobachmann/bank-marketing-dataset))
---

### Objective:
Determine how to improve the success of future telemarketing campaigns for term deposits. Central question:
> **"How can we optimize the next telemarketing campaign for term deposits?"**

---

## Key Research Areas:

### 1. Customer Profile:
#### Demographics & Financial Health:
We'll identify the typical target customer and test these hypotheses:
  
- Customers with loans are less likely to opt for term deposits.
- Lower account balances correlate with a lower likelihood of accepting term deposits.
- Younger clients are less inclined towards term deposits.

<font color='orange'>

   -> Problem type: correlation
   <br>
   --> Anticipated method (visualization): Pearson correlation matrix (heat map), Chi-Square test for Independence (contigency table)

</font>
---

### 2. Telemarketing Strategy:
#### Timing & Approach:
We'll look for the best times and methods of contact. We'll examine:
  
- Seasonal effects on deposit decisions.

<font color='orange'>

   -> Problem type: statistical significance
   <br>
   --> Anticipated method (visualization): Time series analysis (plot chart over time)

</font>

- The optimal number of calls to determine customer interest.
- The needed break between two term deposit offers.

<font color='orange'>

   -> Problem type: descriptive 
   <br>
   --> Anticipated method (visualization): descriptive analysis (bar chart)

</font>

---

### 3. Predictive Analysis:
#### Customer Response:
Using machine learning, we'll predict the likelihood of a customer agreeing to a term deposit based on available data.


<font color='orange'>

   -> Problem type: binary classification
   <br>
   --> Anticipated method (visualization): Logistic Regression, Gaussian Bayes NB model (plot)

</font>

---

### 4. Financial Analysis:
#### Deposit Amount Factors:
We'll identify what factors influence the amount a customer chooses to deposit.


<font color='orange'>

   -> Problem type: feature selection
   <br>
   --> Anticipated method (visualization): Random Forest (table)

</font>