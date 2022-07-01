# Using Machine Learning. Predicting outlet sales 


**Author**: Jason Cledgett

### Business problem:

Can an outlet predict sales using the following variables. Item Weight, Item Visibility, Item MRP, Item Type, Item Fat Content, Outlet Size, Outlet Type and Outlet Location Type


### Data:
Dataset includes 8,523 rows with 12 columns. Item_Weight is missing 1463 rows and Outlet Size is missing 2410 rows. 


## Methods
- To prep the data for Machine Learning columns where categorized into features (Numeric, Ordinal, Nominal)
- To handle missing data, the mean was applied to Item Weight and Most Frequent was applied to outlet size

## Results

#### Total Sales by item identifier
- Higest total sales for a single item in an outlet $13,086. 
- Min total sales for a single item in an outlet $33.
- Average total sales for a single item in an outlet $2181
![Total Sales](https://github.com/cledgeja/coding_dojo/blob/749877ee5d2bb565440c4493dc8c197e2ace6d1c/Machine_Learning/Projects/images/total%20sales%20by%20item%20and%20outlet.png)


#### Decision Tree Test Actual vs Prediction
##### Testing average difference in actual vs predicted (RMSE) $1,057.44 with model explaining 59% of variance predicting sales (r2)
![Decision Tree](https://github.com/cledgeja/coding_dojo/blob/328b72115000eeeecd34f38996f3fccbc96b0423/Machine_Learning/Projects/images/Decision%20Tree%20Outlet%20Sales%20Analysis.png)

## Model

The Decision Tree was the best fit model vs Linear Regression for this project. This models r2 score expalins 59% of the variance in predicting the total sales of an item in an outlet based on Item Weight, Item Visibility, Item MRP, Item Type, Item Fat Content, Outlet Size, Outlet Type and Outlet Location Type. The average root mean square (RMSE) is $1057.44. RMSE is an average of the difference in actual vs predicted with penality (higher error) for the model making larger errors. Choosing a lower RMSE is beneficial because all models will have differences between the actual and predicted values but it better to have a lot small errors vs a few very large errors. 

## Recommendations:

I would reccomend cleaning up this dataset for missing values in Item Weights and Outlet Size and running the model again.


## Limitations & Next Steps

Having a model that explains 59% of the prediction in Sales is decent. Next steps would be to either add more data and or variables.
