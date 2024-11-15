# EXNO: 5 DATA VISUALIZATION USING MATPLOT LIBRARY

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
x1=[1,2,3]
y1=[2,4,6]
plt.plot(x1,y1,label='line1')
x2=[1,2,3]
y2=[4,3,7]
plt.plot(x2,y2,label='line2')
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Two lines on same graph!')
plt.legend()
plt.show()
```
![image](https://github.com/user-attachments/assets/28bb13f0-6ba2-42b3-aaf1-baf960b73b8f)

```
import matplotlib.pyplot as plt
x=[1,2,3,4,5,6]
y=[7,5,6,8,4,2]
plt.plot(x,y,color='green',linestyle='dashed',linewidth=3,marker='o',markerfacecolor='blue',markersize=12)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('innovative customization!')
plt.show()
```
![image](https://github.com/user-attachments/assets/f62bf0a2-e2e4-4157-b1b4-af85f8a8b3ca)

```
yield_fruits=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(yield_fruits)
```
![image](https://github.com/user-attachments/assets/fd2e0c77-a327-475b-b8d9-17455cb47582)

```
years=[2010,2011,2012,2013,2014,2015]
yield_fruits=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yield_fruits)
```
![image](https://github.com/user-attachments/assets/1c84e6bc-18ec-49a6-9ea7-9cda3d948b0e)

```
years=range(2000,2012)
apples=[0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
oranges=[0.926,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896, ]
plt.plot(years, apples)
plt.plot(years, oranges)
plt.xlabel('Year')
plt.ylabel('Yield (tons per hectare)')
plt.title('Crop Yields')
plt.legend(['Apples','Oranges']);
```
![image](https://github.com/user-attachments/assets/8d3d4e9a-4a7a-4a65-bcd2-da1e83dda3a5)

```
plt.figure(figsize=(12,6))
plt.plot(years,oranges,marker='o')
plt.title("Yield of Oranges (tons per hectare)");
```
![image](https://github.com/user-attachments/assets/94ef978d-4205-4979-9c44-59d08574ce1f)

```
import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
x=np.arange(0,10)
y=np.arange(11,21)
x
```
![image](https://github.com/user-attachments/assets/c6ab0671-6fb3-4f1a-b1dd-5cc494bccd38)

```
y
```
![image](https://github.com/user-attachments/assets/4cd6aa41-5332-47dd-8426-ef09d99728e5)

```
plt.scatter(x,y,c='r')
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.title('Graph in 2D')
plt.savefig('Test.png')
```
![image](https://github.com/user-attachments/assets/43ea143d-50fe-447f-bddf-0245b90c6f4e)

```
y=x*x
y
```
![image](https://github.com/user-attachments/assets/8ccd12c3-4f06-41c2-82d5-e82489b94f00)

```
plt.plot(x,y,'b*',linestyle='dashed',linewidth=2,markersize=12)
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('2d Diagram')
```
![image](https://github.com/user-attachments/assets/b2efd0c4-aa53-44c2-aef6-eb254945279e)

```
np.pi
```
![image](https://github.com/user-attachments/assets/3408c49f-b91e-42ba-9def-f2f8e83abf3f)

```
x=np.arange(0,4*np.pi,0.1)
y=np.sin(x)
plt.title("sine wave form")
plt.plot(x,y)
plt.show()
```
![image](https://github.com/user-attachments/assets/e2691af6-b091-4cd6-88ce-c072fe70a690)

```
import matplotlib.pyplot as plt
import numpy as np
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color='blue')
plt.fill_between(x,y2,color='violet')
```
![image](https://github.com/user-attachments/assets/e1115628-7a85-41fa-8f8e-71e8688491a8)

```
import matplotlib.pyplot as plt
import numpy as np
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color='blue')
plt.fill_between(x,y2,color='violet')

plt.plot(x,y1,color='red')
plt.plot(x,y2,color='black')
plt.legend(['y1','y2'])
plt.show()
```
![image](https://github.com/user-attachments/assets/6f31ddea-42c6-4fd9-af31-93518a1a5d03)

```
import matplotlib.pyplot as plt
height=[10,24,36,40,5]
names=['one','two','three','four','five']
c1=['pink','green']
c2=['b','g']
plt.bar(names,height,width=0.8,color=c1)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My bar chart!')
plt.show()
```
![image](https://github.com/user-attachments/assets/24d868f9-d6a4-4229-8b1b-f6f7876dc4d5)

```
x=[2,8,10]
y=[11,16,9]
x2=[3,9,11]
y2=[6,15,7]
plt.bar(x,y,color='b')
plt.bar(x2,y2,color='g')
plt.title('Bar graph')
plt.ylabel('Y axis')
plt.xlabel('X axis')
plt.show()
```
![image](https://github.com/user-attachments/assets/da39723d-50af-4d0a-902d-afc98137661a)

```
import matplotlib.pyplot as plt
ages=[2,5,70,40,30,45,50,45,43,40,44,60,7,13,57,18,90,77,32,21,20,40]
range=(0,100)
bins=10
plt.hist(ages,bins,range,color='red',histtype='bar',rwidth=0.8)
plt.xlabel('age')
plt.ylabel('No. of people')
plt.title('My histogram')
plt.show()
```
![image](https://github.com/user-attachments/assets/0e2414f6-bb90-415a-8612-8c2ee8df8cf1)

```
import matplotlib.pyplot as plt
import numpy as np
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data
```
![image](https://github.com/user-attachments/assets/1d296cbb-9e68-43c1-8861-a1a2330e1d52)

```
fig,ax=plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box Plot')
```
![image](https://github.com/user-attachments/assets/03b5fced-a99a-4498-87a2-d15e63ffb1ad)

```
labels='Python','C++','Ruby','Java'
sizes=[215,130,245,210]
colors=['pink','green','blue','red']
explode=(0,0.4,0,0.5)
plt.pie(sizes,explode=explode,labels=labels,colors=colors,autopct='%1.1f%%',shadow=True)
plt.axis('equal')
plt.show()
```
![image](https://github.com/user-attachments/assets/0a43ab6a-3a81-4c32-8f9b-a1f2ddb1a3f4)

```
activities=['eat','sleep','work','play']
slices=[3,7,8,6]
colors=['r','y','g','b']
plt.pie(slices,labels=activities,colors=colors,startangle=90,shadow=True,explode=(0,0,0.1,0),radius=1.2,autopct='%1.1f%%')
plt.legend()
```
![image](https://github.com/user-attachments/assets/a41fc91e-b75c-4944-b8d1-718b7cc17779)

# Result:
Thus, The implementation of data visualization using matplotlib has been successfully verified.
 
