# Neural_Network_Charity_Analysis

# Overview:

The purpose - using Machine Learning and Neural Network to create a binary classifier to determine if applicants will be successful if funded by Alphabet Soup. The network will analyze 34000 past applications that received funding over the years. The dataset contains information about the organization's affiliated industry, government classification, type of organization, income amount, special considerations, amount of funding requested, active statu and if they are successful.

# Results

## Data Preprocessing

* The target/dependent column will be the ‘IS_SUCCESSFUL’ column. The model will predict whether the nonprofit will be successful based on the independent/feature columns.
* The features/independent columns are ‘APPLICATION_TYPE’, ‘AFFILIATION’, ‘CLASSIFICATION’, ‘USE_CASE’, ‘ORGANIZATION’, ‘STATUS’, ‘INCOME_AMT’, ‘SPECIAL_CONSIDERATIONS’, ‘and ‘ASK_AMT’ 
* The columns which would make no impact on the target are the ‘EIN’ and ‘NAME’ columns 

## Summary 
The deep learning model predicted approximately 73.03% of the data correctly which did not meet the tagret of 75%. While in some cases, this may be adequate, for Alphabet Soup’s purpose, the percentage would need to be higher. 

In conclusion, the model  is a good start for accurate predictions. However, to help Alphabet Soup, we would need to adjust the model to allow for improvements  fand further more accurate results.
