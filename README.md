# EXNO-6-DS-DATA VISUALIZATION USING SEABORN LIBRARY

# Aim:
To Perform Data Visualization using seaborn python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1: Include the necessary Library.

STEP 2: Read the given Data.

STEP 3: Apply data visualization techniques to identify the patterns of the data.

STEP 4: Apply the various data visualization tools wherever necessary.

STEP 5: Include Necessary parameters in each functions.

# Coding and Output:
```
import seaborn as sns
df=sns.load_dataset("tips")
df.head()

# Correlation Matrix
df.corr()
sns.heatmap(df.corr())

# Joint plot
# Univarate Analysis
sns.jointplot(x='tip',y='total_bill',data=df,kind='hex')
sns.jointplot(x='tip',y='total_bill',data=df,kind='reg')

# Pair Plot
sns.pairplot(df)
sns.pairplot(df,hue='sex')

# Dist Plot
sns.distplot(df['tip'])
sns.distplot(df['tip'],kde=False,bins=10)

## CATEGORICAL PLOTS
# Count plot
sns.countplot(y='sex',data=df)

# Bar plot
sns.barplot(x='sex',y='total_bill',data=df)
df.head()

# Box Plot
sns.boxplot(x="day", y="total_bill", data=df,palette='rainbow')

# Violin Plot
sns.violinplot(x="total_bill", y="day", data=df,palette='rainbow')
```

<img width="439" height="223" alt="image" src="https://github.com/user-attachments/assets/cda9b3a8-8e3c-4374-9949-6bf9c1387ec9" />

<img width="318" height="145" alt="image" src="https://github.com/user-attachments/assets/cf163078-3e40-4cd1-aad6-bc8200517b57" />

<img width="647" height="563" alt="image" src="https://github.com/user-attachments/assets/9f2c0e09-0f36-4166-82bd-40b4af7c09f8" />

<img width="734" height="773" alt="image" src="https://github.com/user-attachments/assets/03f25d46-7b1d-40a4-83c2-b9581fdb7cd6" />

<img width="741" height="746" alt="image" src="https://github.com/user-attachments/assets/2d2f8a76-ee61-4108-a6bf-0f39f1be0124" />

<img width="933" height="823" alt="image" src="https://github.com/user-attachments/assets/775e57b4-f426-42cf-b1b6-b9abb424442c" />

<img width="1062" height="818" alt="image" src="https://github.com/user-attachments/assets/965a0411-225a-4a50-a7d7-76a2fe27e686" />

<img width="717" height="545" alt="image" src="https://github.com/user-attachments/assets/e363ed52-5ecb-4a4d-b6ee-02eee6ddbb10" />

<img width="753" height="585" alt="image" src="https://github.com/user-attachments/assets/2e8d8cf9-3caa-40eb-99bd-4684b5e80a42" />

<img width="705" height="758" alt="image" src="https://github.com/user-attachments/assets/6722761f-01c9-4123-bd15-c8dddd9e1d5c" />

<img width="706" height="574" alt="image" src="https://github.com/user-attachments/assets/964d8f35-a0bc-4ece-934b-a7c68e5c0c87" />

<img width="720" height="584" alt="image" src="https://github.com/user-attachments/assets/7e11c287-1362-4474-bc13-6163630196fe" />

# Result:
Thus, performing Data Visualization using seaborn python library for the given datas has been executed successfully.
