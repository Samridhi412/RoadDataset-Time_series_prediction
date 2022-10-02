# RoadDataset-Time_series_prediction
#Dataset Description
Dataset Road has data regarding road where length is approx 25kms and full length road is further divided into around 100 subsections.
There are around 13 parameters, 10 rows per section, 10 rows show data collected for 10 years
#Task In Hand
Determine value of parameters 9-13 for 10th year for each of 100 sections
Plot graph depicting the comparison between sensor values and predicted values
#Methodology
Import Road Dataset
Renamed column(Unnamed to sub_section) and replaced Nan with corresponding section name
Define test_data by extracting 10th  row from each section
Transformed the Data into Train and Test Dataset, by extracting 10th year data for parameters 9-13 for every section. Applied Extra Regressor Model, Decision Tree Classifier and Random Forest to compare the results
Best RMSE=41.49268845443712 from Decision tree Classifier
Plot scatter-plot between Predicted and True values for parameters 9-13
