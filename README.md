# Study of the Effects of Climate Change on Crop Yields
## Prediction of crop yields based on climate variables using machine learning algorithms 
![dataset-cover](https://user-images.githubusercontent.com/39447236/222884458-65707c2b-bade-4bfe-a41a-80e024cdabaf.jpg)

## Data
The data contains 28242 rows and 7 columns  
  
![Screenshot 2023-03-04 095913](https://user-images.githubusercontent.com/39447236/222884543-ef5eef10-e35f-4fe0-bb56-97b8c40ae563.png)

### the columns are :  
1- Area  
2- Crop  
3- Year  
4- Average rain fall mm per year  
5- Pesticides tonnes  
6- Average temperature  
7- hg/ha_yield (Output)  
## Data Analysis
![Screenshot 2023-03-04 100232](https://user-images.githubusercontent.com/39447236/222884637-960c37ee-9b79-4fa8-a349-a47c224c84d0.png)
![Screenshot 2023-03-04 100315](https://user-images.githubusercontent.com/39447236/222884667-7a5d7341-2aeb-4f9a-aca8-c0e32f8c22ff.png)
![Screenshot 2023-03-04 100419](https://user-images.githubusercontent.com/39447236/222884694-042bf2e2-f60f-403b-bcca-9240d2f5828a.png)

## Preprocessing
1- Dropped the "Year" column because it has no relevance  
2- Hot encoded categorical data usnig pandas get dummis  
3- Split the data into X (features) and Y (output)  
4- Normalized the feature columns to be between 0 and 1  
5- Split the data into 80% for training and 20% for testing  
## Prediction
1- Used LazyPredict library to compare the results of multiple regression algorithms  
  
![Screenshot 2023-03-04 100539](https://user-images.githubusercontent.com/39447236/222884758-0b02fef1-4f4e-42ae-ad6e-571f96040957.png)

2- Use Random Forest Regressor for regression as it has the best accuracy  
  
![Screenshot 2023-03-04 100715](https://user-images.githubusercontent.com/39447236/222884810-502ac00e-ffe6-4a48-a386-07d9fc672de2.png)
