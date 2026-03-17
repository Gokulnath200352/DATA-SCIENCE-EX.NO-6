# EXNO-6-DS-DATA VISUALIZATION USING SEABORN LIBRARY

# Aim:
  To Perform Data Visualization using seaborn python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding 
```
import seaborn as sns
import matplotlib.pyplot as plt
df=sns.load_dataset("iris")
df.head()
corr_matrix=df.select_dtypes(include=["float64"]).corr()
sns.heatmap(corr_matrix, annot=True, cmap="coolwarm")
plt.show()
sns.jointplot(x='sepal_length',y='sepal_width',data=df,kind='hex')
sns.jointplot(x='sepal_length',y='sepal_width',data=df,kind='reg')
sns.pairplot(df)
sns.pairplot(df,hue='species')
sns.distplot(df['sepal_width'])
sns.distplot(df['petal_length'],kde=False,bins=10)
sns.countplot(x='species',data=df)
sns.countplot(y='species',data=df)
sns.barplot(x='sepal_length',y='sepal_width',data=df)
sns.boxplot(x='sepal_length',y='sepal_width',data=df)
sns.boxplot(x='sepal_length',y='sepal_width',data=df,palette='rainbow')
sns.boxplot(data=df,orient='v')sns.boxplot(x='sepal_length',y='sepal_width',data=df,hue='species')
sns.violinplot(x='sepal_length',y='sepal_width',data=df,palette='rainbow')

```
# Output
<img width="646" height="218" alt="Screenshot 2026-03-16 202906" src="https://github.com/user-attachments/assets/d33d901e-08f8-4117-bb5b-c3d60f214990" />
<img width="673" height="540" alt="Screenshot 2026-03-16 202916" src="https://github.com/user-attachments/assets/daed5597-cb3a-471c-b6b5-8143343c95e3" />
<img width="785" height="738" alt="Screenshot 2026-03-16 202935" src="https://github.com/user-attachments/assets/d50b95d3-d835-47ef-8348-6445cc6e62dc" />
<img width="787" height="760" alt="Screenshot 2026-03-16 202948" src="https://github.com/user-attachments/assets/9d47d3ab-5363-445c-a276-81f73bc95580" />
<img width="803" height="799" alt="Screenshot 2026-03-16 203012" src="https://github.com/user-attachments/assets/ab1f6792-dd8c-47c6-a1a0-58ce776c596e" />
<img width="816" height="754" alt="Screenshot 2026-03-16 203027" src="https://github.com/user-attachments/assets/cc83712d-b927-478e-953b-4375a1ef427c" />
<img width="772" height="590" alt="Screenshot 2026-03-16 203038" src="https://github.com/user-attachments/assets/ca145dee-0e54-45b7-b1fe-ee3c783c6dd0" />
<img width="699" height="565" alt="Screenshot 2026-03-16 203048" src="https://github.com/user-attachments/assets/f6aea7b3-a18f-4479-b490-edf901c9f345" />
<img width="761" height="566" alt="Screenshot 2026-03-16 203058" src="https://github.com/user-attachments/assets/3c3a26e1-7f4d-4ef9-b0df-7183f6ea3b14" />
<img width="838" height="590" alt="Screenshot 2026-03-16 203107" src="https://github.com/user-attachments/assets/fef9a9e9-8f40-46f6-94ac-93e8cdb39462" />
<img width="780" height="589" alt="Screenshot 2026-03-16 203117" src="https://github.com/user-attachments/assets/c3d8c0e2-b13f-4d01-a528-808177a9782d" />
<img width="802" height="588" alt="Screenshot 2026-03-16 203125" src="https://github.com/user-attachments/assets/a6295bff-6fd3-40d0-9ec5-b2f0e6478e1a" />
<img width="766" height="565" alt="Screenshot 2026-03-16 203134" src="https://github.com/user-attachments/assets/b3543a7f-726d-4a7c-ae2d-a2a83b8190d6" />
<img width="741" height="533" alt="Screenshot 2026-03-16 203143" src="https://github.com/user-attachments/assets/b6104fe0-24b1-409d-8a6a-3bee9f5d9fbb" />
<img width="773" height="598" alt="Screenshot 2026-03-16 203152" src="https://github.com/user-attachments/assets/2d03e167-32a7-4671-8d9d-a7497886a65d" />
<img width="794" height="618" alt="Screenshot 2026-03-16 203201" src="https://github.com/user-attachments/assets/3308bcf7-b36e-4958-933c-d649088ac3fa" />







# Result:
Thus,The data visualization using seaborn library is completed successfully

