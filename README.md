# PORTUGUESE-BANKING-CAMPAIGN

![increase-deposits](https://user-images.githubusercontent.com/122966157/219281346-4a1a4fc3-181c-4ee9-89f0-7aad8ecc8c57.jpg)

          
 #### PROBLEM STATEMENT:

   * The Portuguese bank has experienced a decline in revenue and is looking to determine what actions to take.

   * After investigation, we found out that the root cause is that their clients are not depositing as frequently as they had been previously.

   * Therefore, the Portuguese bank would like to identify existing clients who have a higher chance of subscribing to a term deposit and focus their marketing efforts         on these clients.

#### ABOUT DATASET:

* This is a dataset that describes the results of Portugal's bank marketing campaigns.

* The campaigns conducted were mostly based on direct phone calls, offering bank clients the opportunity to place a term deposit.

* If, after all marking efforts, the client agreed to place a deposit, the target variable was marked as "yes"; otherwise, it was marked as "no".

#### ABOUT PROJECT:

* In this project, I will analyze the bank leads dataset and create a classification algorithm from my perspective.

#### INTENTION OF PROJECT:

* Associate the data

* Displaying the data with summary statistics, missing values, and outliers.

* DATA VISUALIZATION - Using "Matplot and Seaborn".

* DATA EXPLORATION - Using "PANDAS".

* Data Manipulation / Feature Engineering.

* Build the Classification Model - Using "SKLEARN".

* Validate and implement the data model.

#### ABOUT THE FEATURES(In the dataset):

* We have 4118 instances and 21 features. The 21 attributes have been described below in detail.

Age : Age of the lead (numeric)

Job : type of job (Categorical)

Marital : Marital status (Categorical)

Education : Educational Qualification of the lead (Categorical)

Default: Does the lead has any default(unpaid)credit (Categorical)

Housing: Does the lead has any housing loan? (Categorical)

loan: Does the lead has any personal loan? (Categorical)

campaign: number of contacts performed during this campaign and for this client (numeric)

pdays: number of days that passed by after the client was last contacted from a previous campaign(numeric; 999 means client was not previously contacted))

previous: number of contacts performed before this campaign and for this client (numeric)

poutcome: outcome of the previous marketing campaign (categorical)

emp.var.rate: employment variation rate - quarterly indicator (numeric)

cons.price.idx: consumer price index - monthly indicator (numeric)

cons.conf.idx: consumer confidence index - monthly indicator (numeric)

euribor3m: euribor 3 month rate - daily indicator (numeric)

nr.employed: number of employees - quarterly indicator (numeric)

y - has the client subscribed a term deposit? (binary: 'yes','no')

#### EPILOGUE:

* We can clearly see that duration plays an important role in determining the outcome of our dataset.

* It is certain that the more leads that are interested in starting a deposit will have a higher number of calls and the call duration will be higher than average.

* It's a good idea to reach out to leads at the beginning of the new bank period (May-July)  since we've seen data showing positive results in the past.
