# Using Machine Learning. Predicting outlet sales 
## Subtitle describing the analysis 

**Author**: Jason Cledgett

### Business problem:

Can an outlet predict sales with the following variables. Item Weight, Item Visibility, Item MRP, Item Type, Item Fat Content, Outlet Size, Outlet Type and Outlet Location Type


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

Describe your final model

Report the most important metrics

Refer to the metrics to describe how well the model would solve the business problem

## Recommendations:

More of your own text here


## Limitations & Next Steps

More of your own text here
