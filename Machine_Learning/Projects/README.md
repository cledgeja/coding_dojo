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

#### Linear Regression Test Actual vs Prediction
##### Testing average difference in actual vs predicted (RMSE) $1,166.33 with model explaining 51% of variance predicting sales (r2)
![LinearRegression](https://github.com/cledgeja/coding_dojo/blob/328b72115000eeeecd34f38996f3fccbc96b0423/Machine_Learning/Projects/images/Decision%20Tree%20Outlet%20Sales%20Analysis.png)

> Linear Regression Model predicting outlet sales

#### Decision Tree Test Actual vs Prediction
##### Testing average difference in actual vs predicted (RMSE) $1,057.44 with model explaining 59% of variance predicting sales (r2)
![LinearRegression](https://github.com/cledgeja/coding_dojo/blob/57c2c9447df421db996cb089b731877e924150ef/Machine_Learning/Projects/images/LinearModel%20Results%20Outlet%20Sales%20Analysis.png)

## Model

Describe your final model

Report the most important metrics

Refer to the metrics to describe how well the model would solve the business problem

## Recommendations:

More of your own text here


## Limitations & Next Steps

More of your own text here
