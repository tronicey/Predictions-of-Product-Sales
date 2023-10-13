# Predictions of Product Sales
## Connection between Item Outlet Sales and and Fat Content and Models to Find Item Outlet Sales
 
 Author: Tronice Ray

 ## Business Problem
 How accurately can we find the Item Outlet Sales.
 

### This project shows the relation between low fat and regular fat items sales. Which sales better and if we see any connection as to why that is.
  
- Looking at sales of items based on fat content, we found low fat items sold more in comparison to regular fat items.
 ![Unknown](https://github.com/tronicey/Predictions-of-Product-Sales/assets/143138682/7d6d969d-be49-4685-ae32-147e150bf40e)

- Comparing the histogram chart to the multivariate countplot, you get a better understanding as to why low fat items sold more. There are three categories that are only low fat and there are no categories that are only regular fat.
![Unknown-2](https://github.com/tronicey/Predictions-of-Product-Sales/assets/143138682/b8762284-fa44-4532-9cfd-7aff87968940)

- The heat map shows a negative correlation between Item Outlet Sales and Item Weight and Outlet Establishment year.
![image](https://github.com/tronicey/Predictions-of-Product-Sales/assets/143138682/24928928-39f3-48fb-acf5-bd52a534a529)

## Summary of the model and its evaluation metrics
R^2 feature in the Regression Test Data shows a 53% chance of calculating the correct Item Outlet Sales. Showing we may need to go back and try other models to better find the correlation between the features and the target.

## LinearRegression coefficients plot.
![image](https://github.com/tronicey/Predictions-of-Product-Sales/assets/143138682/d4134564-0b17-4127-ba3f-dbc6d144ad17)

This graph shows the most impactful features. Item_MRP, Outlet_Type_Grocery Store and Item_Visibility. Item_MRP is the most impactful feature. Outlet_Type_Grocery Store is also a strong feature, while Item_Visibility is not as important

## Tree-based model's feature importances.
![image](https://github.com/tronicey/Predictions-of-Product-Sales/assets/143138682/c9ebb5b6-fab7-4dea-815c-74a3558fa1c7)

This graph identifies the top 5 most important features, which are: Item_MRP, Outlet_Type_Grocery Store, Outlet_Type_Supermarket Type 3, Outlet_Identifier_OUT027, and Item_Visibility

## Final recommendations to your stakeholder.
The Item_MRP continues to be the most important feature to finding the Item Outlet Sales followed by Outlet Type Grocery Store. 

