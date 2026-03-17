# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:
```
import matplotlib.pyplot as plt
import numpy as np
x=np.arange(1,75)
y=np.arange(76,151)
x=np.arange(76,100)
y=np.arange(101,125)
plt.scatter(x,y)
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('Graph in 2D')
plt.savefig('iris.png')
plt.plot(x,y,'r*',linestyle='dashed',linewidth=2, markersize=12)
plt.xlabel('X axis')
plt.ylabel('Y axis')
In [24]:
In [12]:
In [13]:
In [14]:
In [17]:
plt.title('2d Diagram')
plt.show()
plt.subplot(2,2,1)
plt.plot(x,y,'r--')
plt.subplot(2,2,2)
plt.plot(x,y,'g*--')
plt.subplot(2,2,3)
plt.plot(x,y,'bo')
plt.subplot(2,2,4)
plt.plot(x,y,'go')
plt.show()
x = np.arange(1,151)
y = 3 * x + 5
plt.title("iris.csv")
plt.xlabel("x axis")
plt.ylabel("y axis")
plt.plot(x,y)
plt.show()
np.pi
3.141592653589793
x = np.arange(0, 4 * np.pi, 0.1)
y = np.sin(x)
plt.title("sine wave form")
plt.plot(x, y)
plt.show()
x = np.arange(0, 5 * np.pi, 0.1)
y_sin = np.sin(x)
y_cos = np.cos(x)
plt.subplot(2, 1, 1)
plt.plot(x, y_sin,'r--')
plt.title('Sine')
plt.subplot(2, 1, 2)
plt.plot(x, y_cos,'g--')
plt.title('Cosine')
plt.show()
x = [2,8,10]
y = [11,16,9]
x2 = [3,9,11]
y2 = [6,15,7]
plt.bar(x, y)
plt.bar(x2, y2, color = 'g')
plt.title('Bar graph')
plt.ylabel('Y axis')
plt.xlabel('X axis')
plt.show()
a = np.array([22,87,5,43,56,73,55,54,11,20,51,5,79,31,27])
plt.hist(a)
plt.title("histogram")
plt.show()
data = [np.random.normal(0, std, 100) for std in range(1, 4)]
plt.boxplot(data,vert=True,patch_artist=False);
plt.show()
data = [np.random.normal(0, std, 100) for std in range(1, 4)]
plt.boxplot(data,vert=True,patch_artist=True);
plt.show()
labels = 'Python', 'C++', 'Ruby', 'Java'
sizes = [215, 130, 245, 210]
colors = ['gold', 'yellowgreen', 'lightcoral', 'lightskyblue']
explode = (0.4, 0, 0, 0)
plt.pie(sizes, explode=explode, labels=labels, colors=colors,
autopct='%1.1f%%', shadow=False)
plt.axis('equal')
plt.show()
```

# Output

<img width="718" height="506" alt="Screenshot 2026-03-16 194421" src="https://github.com/user-attachments/assets/c677d13a-1537-4510-8050-4a843ad5d3a6" />
<img width="680" height="518" alt="Screenshot 2026-03-16 194439" src="https://github.com/user-attachments/assets/d87e9be0-2929-4f83-9c1b-31139cd6286f" />
<img width="677" height="501" alt="Screenshot 2026-03-16 194451" src="https://github.com/user-attachments/assets/f4b98510-5a3a-4496-95e6-1e391495aea5" />
<img width="735" height="536" alt="Screenshot 2026-03-16 194509" src="https://github.com/user-attachments/assets/0365590e-b8e0-4949-8313-ec431fc6b618" />
<img width="686" height="534" alt="Screenshot 2026-03-16 194519" src="https://github.com/user-attachments/assets/51ba6d2a-ca29-4dcb-b20e-5105cc067526" />
<img width="692" height="524" alt="Screenshot 2026-03-16 194530" src="https://github.com/user-attachments/assets/74c22cc1-6275-4bbd-8a7c-24891eb59321" />
<img width="752" height="552" alt="Screenshot 2026-03-16 194540" src="https://github.com/user-attachments/assets/3a11ac5c-b691-4857-b419-499f51804b0e" />
<img width="701" height="539" alt="Screenshot 2026-03-16 194550" src="https://github.com/user-attachments/assets/3770ddc4-2269-4d7c-8d88-d405f1c7b471" />
<img width="621" height="476" alt="Screenshot 2026-03-16 194601" src="https://github.com/user-attachments/assets/34799a75-b724-40f9-b8a6-f70d3cd51ff8" />
<img width="634" height="477" alt="Screenshot 2026-03-16 194612" src="https://github.com/user-attachments/assets/ab01d091-88ef-45de-89a1-a5a89855c8c5" />
<img width="494" height="419" alt="Screenshot 2026-03-16 194623" src="https://github.com/user-attachments/assets/aded2ffc-9eec-45b0-bb40-abd583a04ce2" />

# Result:

Thus , The data visualization using matplotlib library is completed successfully

