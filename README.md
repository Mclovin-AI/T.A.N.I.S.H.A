# ML_DATAFRAME(CARS)
#dataset 2nd hand car yha hm feature enginering and statical eng 
import pandas as pd
df=pd.read_csv(r"C:\Users\dell\Downloads\Car(1).csv").iloc[:,1:]   #yha hm ne phela coulum uda dea 
df.head()

#topredict the price of 2nd hand car

df.info() #to get info like no of rows column ,datatype etc
