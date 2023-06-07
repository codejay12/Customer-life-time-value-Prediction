# Problem Statement

The goal of this project is to develop a model that can predict the Customer Lifetime Value (CLV) for an auto insurance company. The CLV is a crucial metric that estimates the total income a business can expect from a typical customer over their entire tenure as a client. By accurately predicting the CLV, the insurance company can make informed decisions regarding customer segmentation, pricing strategies, and resource allocation.

# Features

The prediction of CLV is based on a combination of quantitative and qualitative features. These features include:

- 'Coverage': The type of coverage the customer has chosen.
- 'Education': The educational background of the customer.
- 'EmploymentStatus': The employment status of the customer.
- 'Gender': The gender of the customer.
- 'Income': The income level of the customer.
- 'Location.Geo': The geographic location of the customer.
- 'Location.Code': The postal code of the customer's location.
- 'Marital.Status': The marital status of the customer.
- 'Monthly.Premium.Auto': The monthly premium paid by the customer for auto insurance.
- 'Months.Since.Last.Claim': The number of months since the customer's last claim.
- 'Months.Since.Policy.Inception': The number of months since the inception of the customer's policy.
- 'Number.of.Open.Complaints': The number of open complaints filed by the customer.
- 'Number.of.Policies': The number of insurance policies held by the customer.
- 'Policy.Type': The type of insurance policy held by the customer.
- 'Policy': The specific policy ID.
- 'Renew.Offer.Type': The type of renewal offer received by the customer.
- 'Sales.Channel': The sales channel through which the customer was acquired.
- 'Total.Claim.Amount': The total claim amount for the customer.
- 'Vehicle.Class': The class of the insured vehicle.
- 'Vehicle.Size': The size category of the insured vehicle.

# Models Used

For this project, various machine learning models were employed to predict the CLV. The models used include:

1. Linear Regression
2. Ridge Regression
3. Decision Trees
4. Support Vector Machines (SVM)
5. Random Forest
6. Boosted Trees
7. k-Nearest Neighbors (KNN) Regressor

These models were chosen for their ability to handle both numerical and categorical features, and their effectiveness in capturing complex relationships within the data. By comparing the performance of these models, we can identify the most accurate and reliable approach for predicting the CLV.

# Instructions for Running the Code

1. Install the required dependencies listed in the 'requirements.txt' file.
2. Run the 'main.py' script to initiate the CLV prediction model.
3. Provide the necessary input data in the required format.
4. The model will generate predictions for the CLV based on the provided input features.

Note: Additional instructions or specific data formatting requirements may be provided in the code files or documentation as necessary.
