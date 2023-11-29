# My_Practice
import pandas as pd
#  rerad the data 
df=pd.read_csv('./data/data.csv')
# write the data 
df.to_excel('awien_wala_data.xlsx')
# reading xcl  file
df_xl=pd.read_excel('awien_wala_data.xlsx')
# PRINT THE VARIABLE AND DATA IN TERMINALS
print (df)

