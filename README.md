# Data-Hack's-JOB-A-THON
## Health Insurance Lead Prediction(HILP) hackathon conducted by Data Hack.
### Problem Statement
Your Client FinMan is a financial services company that provides various financial services like loan, investment funds, insurance etc. to its customers. FinMan wishes to cross-sell health insurance to the existing customers who may or may not hold insurance policies with the company. The company recommend health insurance to it's customers based on their profile once these customers land on the website. Customers might browse the recommended health insurance policy and consequently fill up a form to apply. When these customers fill-up the form, their Response towards the policy is considered positive and they are classified as a lead.

Once these leads are acquired, the sales advisors approach them to convert and thus the company can sell proposed health insurance to these leads in a more efficient manner.

Now the company needs your help in building a model to predict whether the person will be interested in their proposed Health plan/policy given the information about:

- Demographics (city, age, region etc.)
- Information regarding holding policies of the customer
- Recommended Policy Information  

Before building the model data-preprocessing is done and exploratory data analysis on the dataset is done. Here's the `.ipynb` file of [EDA](https://github.com/jajinkya/Data-Hack-s-JOB-A-THON/blob/main/HILP_EDA.ipynb).  
Then to build a model; since the dataset contains more categorical features columns so **Catboost** algorithm is used. And to optimize the model we need to tune the hyperparameter's of the algorithm. For that, used `skopt's` **BayesianSearchCV** algorithm. And get finalized model. Here's the [Model](https://github.com/jajinkya/Data-Hack-s-JOB-A-THON/blob/main/Final_Submission.ipynb).  
To read about the detailed approach. Here's [the report of the project](https://github.com/jajinkya/Data-Hack-s-JOB-A-THON/blob/main/HILP_EDA.ipynb).
