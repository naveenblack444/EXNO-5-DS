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
 import pandas as pd
 import numpy as np
 import seaborn as sns
 import matplotlib.pyplot as plt
```
```
 marks=[13,45,63,78]
 student=['ABC','QOR','EFB','TOB']
 plt.plot(marks,student)
 plt.xlabel('Marks')
 plt.ylabel('Student name')
 plt.show()
 student=['A','B','C','D']
 attendence=[90,85,73,88]
 plt.plot(attendence,student)
 plt.xlabel('Attendence')
 plt.ylabel('Student name')
 plt.show()
```
# output 
<img width="722" height="533" alt="image" src="https://github.com/user-attachments/assets/a9c7bcea-16d7-432c-9442-cd58f80526eb" />

<img width="688" height="555" alt="image" src="https://github.com/user-attachments/assets/3cf2f65d-e081-40f6-8e77-4244e8f25794" />

```
 x=[10,20,30,40,50]
 y=[100,200,300,400,500]
 plt.scatter(x,y,label='stars',color='green',marker='*',s=30)
 plt.show()
 x=np.arange(0,15)
 y=np.arange(0,15)
 x
 y
 plt.scatter(x,y,c='r')
 plt.xlabel('X axis')
 plt.ylabel('y axis')
 plt.title('Scatter plot')
 plt.show()
```

# output 
<img width="691" height="519" alt="image" src="https://github.com/user-attachments/assets/18778ed5-c613-4424-b939-618dc4c8c9cc" />

<img width="699" height="574" alt="image" src="https://github.com/user-attachments/assets/ddd08ff7-2599-43f6-90e1-e0fb9904cf55" />

```
 act=['eat','sleep','work','play']
 slices=[3,7,8,6]
 color=['r','y','g','b']
 plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
 plt.legend()
 plt.show()
 feedback=['Good','excellent','Perfect','Ok']
 slices=[4,10,3,8]
 color=['y','r','b','g']
 plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
 plt.legend()
 plt.show()
```

# output 
<img width="569" height="517" alt="image" src="https://github.com/user-attachments/assets/3516b139-57c8-4546-aeb0-38b01aab5dc4" />

<img width="550" height="496" alt="image" src="https://github.com/user-attachments/assets/aa432f98-746d-4975-8328-21275b71dbd0" />


```
 x = [1, 2, 3, 4, 5]
 y1 = [10, 12, 14, 16, 18]
 y2 = [5, 7, 9, 11, 13]
 y3 = [2, 4, 6, 8, 10]
 plt.fill_between(x, y1, color='blue')
 plt.fill_between(x, y2, color='green')
 plt.plot(x, y1, color='red')
 plt.plot(x, y2, color='black')
 plt.legend(['y1','y2'])
 plt.show()
```

# output 
<img width="691" height="517" alt="image" src="https://github.com/user-attachments/assets/0c6d34b3-0bba-4f3f-a66b-51bee4a04660" />

```
 height = [10, 24, 36, 40, 5]
 names = ['one', 'two', 'three', 'four', 'five']
 c1=['red', 'green'] 
 c2=['b', 'g']
 plt.bar (names, height, width=0.8, color=c1)
 plt.xlabel('x - axis')
 plt.ylabel('y - axis')
 plt.title('My bar chart!')
 plt.show()
```

# output 
<img width="701" height="572" alt="image" src="https://github.com/user-attachments/assets/5988ee03-1053-46dd-b9ab-785d771da123" />

```
 x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
 plt.hist(x, bins = 10, color='blue', alpha=0.5)
 plt.show()
```

# output 
<img width="668" height="520" alt="image" src="https://github.com/user-attachments/assets/cb1eac32-d5cc-47ce-aa23-ef3c8845fd1d" />

```
 np.random.seed(0)
 data=np.random.normal(loc=0, scale=1, size=100)
 data
```

# output 
<img width="878" height="455" alt="image" src="https://github.com/user-attachments/assets/164e3699-ac8e-4cce-9417-97aa00a13f29" />

```
fig, ax= plt.subplots()
 ax.boxplot(data)
 ax.set_xlabel('Data')
 ax.set_ylabel('Values')
 ax.set_title('Box Plot')
```

# output 

<img width="703" height="570" alt="image" src="https://github.com/user-attachments/assets/8bd55549-f9a7-4464-bb7f-ab97d167a21d" />



# Result:
 Thus, all the data visualization techniques of matplotlib has been implemented.
