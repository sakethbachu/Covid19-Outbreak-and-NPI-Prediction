# Coronaob.ai - Pandemic Outbreak and mitigation prediction

# INTRODUCTION

Coronaob.ai is built with the help of AI and statistical methods. This model helps in forecasting the number of cases and also predicts mitigation measures to control the outbreak.

# INSTALL

You can directly use this on Google Collab. Once you click on the the .ipynb file, you will be able to see a button with **Open in Collab**, that will directly take you to Google collab where in you check the code and its flow. Code to install any other additional package is clearly mentioned in the notebook itself.

# Folder guide

1) **Our main notebook**: covid19_outbreak_and_npi_prediction_model1.ipynb, has all the code and is commented at every step for better understanding. It also has references for the techniques which we have used and also on the assumptions which we have taken. Incase if you have a query, you can start an issue thread in this repository.

2) **covid19h**: This folder contains all the necessary datasets that we used in the above-mentioned notebook.

   a)**mastersheetprediction.csv**: This is the main dataset that we have used in our prediction and analysis task.
   
   b)**oversampletargets.csv**: This are the encoded targets i.e labels.
   
   c)**population.csv**: This file contains numbers on population-country wise.
   
   d)**pred.csv**: This is the dataset that is extracted from step 1 and is used in step 2 along with other parameters.
   
   e)**ts_r2.csv**: Ths is the file that contains intermediate values while using R.
   
   f)**w.csv**: This is the file that contains daily min and max temperatures arranged country wise.
   
   g)**w_forecast.csv**: This is the forecast on daily min and max temperatures arranged country wise.
 
 **Every other detail is given in the notebook clearly**
