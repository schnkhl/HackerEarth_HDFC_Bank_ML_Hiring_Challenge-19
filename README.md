# HackerEarth_HDFC_Bank_ML_Hiring_Challenge-19
HackerEarth Banking Behavioral Scorecard for Internal Liability customers (Rank 20 out of 4k+)

# Problem Statement
## Use case A:
Your task is to build a banking behavioral scorecard model for internal customers through a user's liability account and predict the credit risk.
These are low transacting customers. The definition that is used for the target variable is every 30+ or X+ days delinquent twice in forward months. The implementations of the model are as follows:
* Pre-approving customers for cross-selling other products of a bank
* Decide the mode of treatment of customers and specify it as an input for credit underwriting
* Note: You can decide the customer treatment through a graded risk profile of customers.

### What is a Banking behavioral scorecard?
Banking behavioral scorecard is a model that is maintained for a customer based on his liability transactions. Liability transactions are transactions that are transacted by an internal customer of a bank. Internal customers of a bank are the customers who have a savings account (SA) with the bank.

### How can a customer repay a loan?
Customer pays the loan in equal monthly installments (EMIs). Loans get paid through post-dated cheques. Customer also has an option to pay through the Electronic Clearing System (ECS) technique or standing instructions to debit the user's HDFC Bank account with the EMI amount.

### What is the meaning of customer risk profile?
Customer risk profile means the probability of the customer defaulting on his EMI payment.

## Use Case B:
* Describe your approach that you have used to build the model and your reasons for the same
* Describe model segmentation (if any)
* Describe how can your model help banks

## Data description
* Total number of variables: 2395
* Col1 Variable: ID
* Col2 Variable: Target Variable
* Col3 to Col2397 are anonymized features.

The sources of the data that are used for the model are as follows:
* Banking information of the customer.
* Customer savings account or Current Account transaction information for a certain period
* Create additional variables or use any additional alternate sources of information for building the model

## Evaluation criteria
The evaluation criteria for the two use cases are defined as follows:
* Use Case A: Submissions are evaluated based on the F1_score technique. It uses the predicted probability and the observed target with the weighted average.
   
* Use Case B: Submissions are evaluated on the basis of:
  * Customer acquisition strategy
  * Clarity of thought
  * Clarity of understanding of the problem

# F1_score: 0.89
# Rank: 20
