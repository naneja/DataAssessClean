# Data Assessing and Cleaning

This project is on data assessing and cleaning.

The jupyter notebook explains why we need to clean the data and why there may be NaN value in the dataset.

We can use pandas or numpy commands to check if there is NaN values and process these values.

## How to Process NaN values:
* Replace if these records are not significant
  * based on rows, columns, threshold
* Replace the NaN values based on some method
  * Forward Fill, Backward Fill on rows/columns

## Duplicated records
* The dataset may have duplicated records. We can use duplicated function of pandas to see and remove.
* Duplicated records may be checked based on all columns or based on subset of columns


## Output
* After processing NaN values and Duplicated records, we get the cleaned data that can be used for data analysis or visualization.
