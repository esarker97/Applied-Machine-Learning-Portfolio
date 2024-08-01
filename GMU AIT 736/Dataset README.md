BigMart Sales Dataset

This dataset, sourced from BigMart sales data on Kaggle, is split into two CSV files: 'Train_UWu5bXk.csv' and 'Test_u94Q5KV.csv'.

The training dataset contains sales information for products across various BigMart outlets, including the target variable 'Item_Outlet_Sales'. The test dataset has the same structure but without the target variable, as it's intended for making predictions.
Features include Item_Identifier, Item_Weight, Item_Fat_Content, Item_Visibility, Item_Type, Item_MRP, Outlet_Identifier, Outlet_Establishment_Year, Outlet_Size, Outlet_Location_Type, and Outlet_Type.

Preprocessing steps include:

Handling missing values in 'Item_Weight' and 'Outlet_Size'

Encoding categorical variables

Feature engineering: Creating a new feature for outlet age

Advanced feature engineering: Adding polynomial features for 'Item_MRP' and 'Item_Visibility'

The training dataset is used for model development and evaluation, while the test dataset is for generating predictions once the final model is selected.
