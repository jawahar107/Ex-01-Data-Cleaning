# Ex-01_DS_Data_Cleansing
# AIM
To read the given data and perform data cleaning and save the cleaned data to a file.

# Explanation
Data cleaning is the process of preparing data for analysis by removing or modifying data that is incorrect ,incompleted , irrelevant , duplicated or improperly formatted. Data cleaning is not simply about erasing data ,but rather finding a way to maximize datasets accuracy without necessarily deleting the information.

# ALGORITHM
## STEP 1
Read the given Data

## STEP 2
Get the information about the data

## STEP 3
Remove the null values from the data

## STEP 4
Save the Clean data to the file

# CODE
from google.colab import files
Uploaded =files.upload()

import pandas as pd
df = pd.read_csv("credit_data_1.csv")
df
#Duplication:
import pandas as pd
import numpy as np
import seaborn as sns
~df.duplicated()
df=df[~df.duplicated()]
df
#Info:
df.info()
#Number of null values:
df.isnull().sum()
#After cleaning the given values:
df.isnull().sum()

# OUPUT
[EXP1.ipynb - Colaboratory.pdf](https://github.com/jawahar107/Ex-01-Data-Cleaning/files/11068515/EXP1.ipynb.-.Colaboratory.pdf)

