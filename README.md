## Study of the Effects of Climate Change on Crop Yields
### Prediction of crop yields based on climate variables using machine learning algorithms 
#### Data
The data contains 28242 rows and 7 columns  
the columns are :  
1- Area  
2- Crop  
3- Year  
4- Average rain fall mm per year  
5- Pesticides tonnes  
6- Average temperature  
7- hg/ha_yield (Output)  
#### Preprocessing
1- Dropped the "Year" column because it has no relevance  
2- Hot encoded categorical data usnig pandas get dummis  
3- Split the data into X (features) and Y (output)  
4- Normalized the feature columns to be between 0 and 1  
5- Split the data into 80% for training and 20% for testing  
#### Prediction
1- Used LazyPredict library to compare the results of multiple regression algorithms  
2- Chose Random Forest Regressor for regression as it has the best accuracy  
