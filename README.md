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


```

<img width="790" height="827" alt="Screenshot 2025-10-28 113617" src="https://github.com/user-attachments/assets/0304f302-391f-4678-9a95-84de4f6964ec" />




```
student=['A','B','C','D']
attendence=[90,85,73,88]
plt.plot(attendence,student)
plt.xlabel('Attendence')
plt.ylabel('Student name')
plt.show()

```
<img width="835" height="736" alt="Screenshot 2025-10-28 113633" src="https://github.com/user-attachments/assets/8cf1b1ed-3b84-4caf-8660-fede6c43ccf7" />




```
x=[10,20,30,40,50]
y=[100,200,300,400,500]
plt.scatter(x,y,label='stars',color='green',marker='*',s=30)
plt.show()

```

<img width="885" height="664" alt="Screenshot 2025-10-28 113640" src="https://github.com/user-attachments/assets/bfaacf6c-e960-481d-bd5b-629c01fbc6d3" />

```
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



<img width="777" height="835" alt="Screenshot 2025-10-28 113649" src="https://github.com/user-attachments/assets/8d5df682-130a-431f-a1e1-b044e1da8420" />




```
act=['eat','sleep','work','play']
slices=[3,7,8,6]
color=['r','y','g','b']
plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()

```

<img width="1268" height="704" alt="Screenshot 2025-10-28 113700" src="https://github.com/user-attachments/assets/10450373-6a46-4986-b6d3-45cbfcc45501" />

```

feedback=['Good','excellent','Perfect','Ok']
slices=[4,10,3,8]
color=['y','r','b','g']
plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()

```
<img width="1260" height="689" alt="Screenshot 2025-10-28 113709" src="https://github.com/user-attachments/assets/2ea4484c-3e19-43e9-b688-7fc1abb98a1a" />


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

<img width="1161" height="795" alt="Screenshot 2025-10-28 113716" src="https://github.com/user-attachments/assets/bd904c00-1654-4b60-9817-e2b8897e9fda" />


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

<img width="802" height="816" alt="Screenshot 2025-10-28 113727" src="https://github.com/user-attachments/assets/73010d46-59bd-4fcf-9a24-2486728aaccc" />


```

x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x, bins = 10, color='blue', alpha=0.5)
plt.show()

```

<img width="896" height="630" alt="Screenshot 2025-10-28 113738" src="https://github.com/user-attachments/assets/5a73af00-78f6-424e-9b11-7d0c041b980a" />


```

np.random.seed(0)
data=np.random.normal(loc=0, scale=1, size=100)
data

```

<img width="1084" height="563" alt="Screenshot 2025-10-28 113745" src="https://github.com/user-attachments/assets/953a7040-7aea-44cf-9acd-f6f7ee96c859" />


```

fig, ax= plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box Plot')


```

<img width="1031" height="769" alt="Screenshot 2025-10-28 113753" src="https://github.com/user-attachments/assets/1028f243-65fb-407b-afed-0c22b91689c1" />












# Result:
 Thus, all the data visualization techniques of matplotlib has been implemented
