## TRAFFIC MANAGEMENT SYSTEM MODEL 

# Phase 1 : Data Cleaning 
    - Found out nan values in the dataframe 
    - Filled the nan values with mode of the coloumn
    - Splitted time data into hours and minutes
    - Imported onehot encoder to encode the categorical data
    - Added heat map of correlation matrix to the data frame
    - Decoded geohash into Latitudes and Longitudes
    - Normalized Temperature, NumberOfLanes, Latitudes and Longitudes
    - Binary classified the days as we have only 2 days
    - Applied log transform to normalize demand column
    - Applied cyclical transform to convert hour and minute into time_sin and time_cos

