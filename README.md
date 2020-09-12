# Tele-communications Customer Churn

Personal project using the telco customer churn dataset: https://www.kaggle.com/blastchar/telco-customer-churn/data#

The goal of this project will be to implement the K Prototypes clustering algorythm which will allow cluster analysis on a mix of both numerical and categorical data.

The data set consists of information about customers, primarily the services they subscribe to, their time with Telco, some lite demographic information, and considering whether they "churned", or left service, within the last month.

## The Data

The data consists of the following categorical data:
- customerID - unique identifier of the customer
- gender - gender of the customer
- SeniorCitizen - whether the customer is a Senior or not
- Partner - whether the customer has a partner or not
- Dependents - whether the customer has dependents or not
- tenure - the length of the customer's time with Telco in months
- PhoneService - whether the customer has phone service or not
- MultipleLines - whether the customer has multiple lines or not or no phone service
- InternetService - whether the customer has internet service or not
- OnlineSecurity - whether the customer has online security or not or no internet service
- OnlineBackup - whether the customer has online backup service or not or no internet service
- DeviceProtection - whether the customer has device protection or not or no internet service
- TechSupport - whether the customer has tech support or not or no internet service
- StreamingTV - whether the customer has streaming service for TV or not or no internet service
- StreamingMovies - whether the customer has streaming service for movies or not or no internet service
- Contract - whether the customer has month-to-month service or a one- or two-year contract
- PaperlessBilling - whether the customer has paperless billing or not
- PaymentMethod - does the customer pay by Mail-in Check, Electronic check, credit card, or automatic bank transfer
- MonthlyCharges - the amount of the cusotmer's monthly charges
- TotalCharges - the customer's total charges over their tenure
- Churn - whether the customer turned over/left in the last month

Again, the data was pulled from a Kaggle data set and was mostly cleaned to begin with.

## Libraries

These are the libraries that were used for this project:

<insert pic>
  
## EDA

![alt text](https://github.com/zachzazueta/telecom_churn_project/blob/master/charges%20tenure%20payment.png)

It is interesting to see the visible trend of Mailed Checks being used for customers with lower Total Charges and Electronic Checks being the seemingly preferred payment method for customers with higher Total Charges.

![alt text](https://github.com/zachzazueta/telecom_churn_project/blob/master/charges%20tenure%20churn.png)

While it will require additional analysis, there does seem to be a trend that on any given tenure level, it is the customers with the highest Total Charges that appear to Churn (leave Telco services).

