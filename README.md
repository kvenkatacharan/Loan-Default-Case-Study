# Loan-Default-Case-Study

<font color = darkblue > <strong>
Bunjab National Bank (BNB) is a large bank, and often gives out personal and business loans. Off-late the bank is in a lot of financial stress, as a lot of borrowers are not paying their EMI's and hence defaulting on their loans. Some of the borrowers, like PJ Mallya and Mirav Modi have even fled to UK to avoid paying back their loans.<br>
BNB has some data about their past customers, and wants to see if Machine Learning (ML) can be used on this dataset to predict whether certain customers will default on their loans or not. Since BNB plans to use the ML model to decide whether to sanction or reject loans to future customers, it wants to be absolutely sure of the model before deploying it.<br>
To test the ML model performnce, BNB has hidden the target column of a portion of the dataset, and wants you to make predictions on this portion of the dataset based on your best Machine Learning Model.<br>
Since, both precision and recall of the model are equally important to BNB, it has decided to use F1 as a metric to evaluate your ML model.


* __Column Name:-------------------Description__ 
* UniqueID:------------------------------------- Identifier for customers
* disbursed_amount:------------------------- Amount of Loan disbursed
* asset_cost:----------------------------------- Cost of the Asset
* ltv:---------------------------------------------- Loan to Value of the asset
* branch_id:------------------------------------	Branch where the loan was disbursed
* Employment_Type:------------------------	Employment Type of the customer (Salaried/Self Employed)
* State_ID:------------------------------------- State of disbursement
* MobileNo_Avl_Flag:-----------------------	if Mobile no. was shared by the customer then flagged as 1
* Aadhar_flag:--------------------------------- if aadhar was shared by the customer then flagged as 1
* PERFORM_CNS_SCORE_DESCRIPTION:--------- Credit Bureau score category
* PRI_NO_OF_ACCTS:--------------------- count of total loans taken by the customer at the time of disbursement
* PRI_ACTIVE_ACCTS:-------------------- count of active loans taken by the customer at the time of disbursement
* PRI_OVERDUE_ACCTS:----------------- count of default accounts at the time of disbursement
* PRI_CURRENT_BALANCE:------------- total Principal outstanding amount of the active loans at the time of disbursement
* PRIMARY_INSTAL_AMT:-----------------	EMI Amount of the primary loan
* NEW_ACCTS_IN_LAST_SIX_MONTHS:--------------	New loans taken by the customer in last 6 months before the disbursment
* DELINQUENT_ACCTS_IN_LAST_SIX_MONTHS:------- Loans defaulted in the last 6 months
* NO_OF_INQUIRIES:-----------------------	Enquries done by the customer for loans
* loan_default:----------------------------------	Payment default in the first EMI on due date (Target)

