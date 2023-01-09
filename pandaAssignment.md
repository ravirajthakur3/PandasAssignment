# PandasAssignment

Q1. How do you load a CSV file into a Pandas DataFrame?
ans-Import panda as pd
    df=pd.read csv(path)
    

Q2. How do you check the data type of a column in a Pandas DataFrame?
import pandas as pd
for normal
list1=[1,2,3,4,5]
print(type(list1))--1
for each column
df=pd.DataFrame(list1)
result=df.dtypes
result--2

 Q3. How do you select rows from a Pandas DataFrame based on a condition?

 	Name	Age	Stream	Percentage
0	Ankit	21	Math	88
1	Amit	19	Commerce	92
2	Aishwarya	20	Science	95
3	Priyanka	18	Math	70
4	Priya	17	Math	65
5	Shaurya	21	Science	78

Let the condition be Stream=Math
Ans-dff.loc[dff['Stream']=='Math']

Q4. How do you rename columns in a Pandas DataFrame?
A
ns-dff.rename(columns={'Name':'name'},inplace=True)
   or
   dff.rename({'Age':'age'},axis=1,inplace=True)

Q5. How do you drop columns in a Pandas DataFrame?
Ans=dff.drop('age',axis=1,inplace=True)

Q6. How do you find the unique values in a column of a Pandas DataFrame?
Ans=dff['Stream'].unique()

Q7. How do you find the number of missing values in each column of a Pandas DataFrame?
Ans=df.isnull().sum()

Q8. How do you fill missing values in a Pandas DataFrame with a specific value?
ans-df['price'].fillna(value = 0.85, inplace = True)
or
a3=df.fillna({'Age':89,
             'Cabin':0})

Q9. How do you concatenate two Pandas DataFrames?
con1=pd.DataFrame(dfff,index=[0,1])
con2=pd.DataFrame(df,index=[2,3,4])
con_12=[con1,con2]
res=pd.concat(con_12)

Q10. How do you merge two Pandas DataFrames on a specific column?
Ans-a2.merge(a3[['name','salary']])

Q11. How do you group data in a Pandas DataFrame by a specific column and apply an aggregation function?
Ans-pk=a7.groupby('name').sum('salary')
    pk
Q12. How do you pivot a Pandas DataFrame?

Q13. How do you change the data type of a column in a Pandas DataFrame?

Q14. How do you sort a Pandas DataFrame by a specific column?

Q15. How do you create a copy of a Pandas DataFrame?

Q16. How do you filter rows of a Pandas DataFrame by multiple conditions?

Q17. How do you calculate the mean of a column in a Pandas DataFrame?

Q18. How do you calculate the standard deviation of a column in a Pandas DataFrame?

Q19. How do you calculate the correlation between two columns in a Pandas DataFrame?

Q20. How do you select specific columns in a DataFrame using their labels?

Q21. How do you select specific rows in a DataFrame using their indexes?

Q22. How do you sort a DataFrame by a specific column?

Q23. How do you create a new column in a DataFrame based on the values of another column?

Q24. How do you remove duplicates from a DataFrame?

Q25. What is the difference between .loc and .iloc in Pandas?
