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

DEVELOPED BY :NARRA RAMYA

REG NO:212223040128

```
 import pandas as pd
 import numpy as np
 import seaborn as sns
 import matplotlib.pyplot as plt
 x = [1, 2, 3, 4, 5]
 y = [3, 6, 2, 7, 1]
 plt.plot(x,y,label='line1')
```
![image](https://github.com/user-attachments/assets/74be2e0d-8b8f-497e-8142-fc0baf786997)
```
 x1 = [1,2,3]
 y1 = [2,4,1]
 x2 = [1,2,3]
 y2 = [4,1,3]
 plt.plot(x1,y1,label='line1')
 plt.plot(x2,y2,label='line2')
 plt.xlabel('x-axis')
 plt.ylabel('y-axis')
 plt.title('Two lines on same graph!')
 plt.legend()
 plt.show()
```
![image](https://github.com/user-attachments/assets/12c3b2c5-a3c2-4889-a166-542a264df3a2)
```
 import matplotlib.pyplot as plt
 x=[1,2,3,4,5,6]
 y=[2,4,1,5,2,6]
 plt.plot(x,y,color='green',linestyle='dashed',linewidth=3,marker='o',markerfacecolor='blue',markersize=12)
 plt.xlabel('x-axis')
 plt.ylabel('y-axis')
 plt.title('Some cool customizations!')
 plt.show()
```
![image](https://github.com/user-attachments/assets/77639cc8-0857-4ab9-8959-ee919873ca4e)
```
 yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
 plt.plot(yield_apples)
```
![image](https://github.com/user-attachments/assets/47348b69-3c38-4300-be21-a1eb4980bd2a)
```
 years=[2010,2011,2012,2013,2014,2015]
 yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
 plt.plot(years,yield_apples)
```
![image](https://github.com/user-attachments/assets/a40a0a99-8d26-412d-8a18-46b86b5543ba)
```
 years=range(2000,2012)
 apples=[0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
 oranges=[0.926,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896, ]
 plt.plot(years, apples)
 plt.plot(years, oranges)
 plt.xlabel('Year')
 plt.ylabel('Yield (tons per hectare)')
 plt.title('Crop Yields in Kanto')
 plt.legend(['Apples','Oranges']);
```
![image](https://github.com/user-attachments/assets/0e4c3c65-5bcf-4e27-9fc2-a047289d5920)
```
 plt.figure(figsize=(12,6))
 plt.plot(years,oranges,marker='o')
 plt.title("Yield of Oranges (tons per hectare)");
```
![image](https://github.com/user-attachments/assets/f7550ef9-5f67-4451-990a-55deb27791b7)
```
 import matplotlib.pyplot as plt
 import numpy as np
 import pandas as pd
 x=np.arange(0,10)
 y=np.arange(11,21)
 x
```
![image](https://github.com/user-attachments/assets/d80ec0dd-ab34-499f-8782-bf4df1181864)
```
y
```
![image](https://github.com/user-attachments/assets/64fc69f6-41aa-43f4-aba6-443b61bf7313)
```
 plt.scatter(x,y,c='r')
 plt.xlabel('X-axis')
 plt.ylabel('Y-axis')
 plt.title('Graph in 2D')
 plt.savefig('Test.png')
```
![image](https://github.com/user-attachments/assets/f3a853c2-41c6-4c28-8324-2f97d4f9cb06)
```
y=x*x
y
```
![image](https://github.com/user-attachments/assets/8b153691-7018-4c55-8891-2c8837123c71)
```
 plt.plot(x,y,'g*',linestyle='dashed',linewidth=2,markersize=12)
 plt.xlabel('X axis')
 plt.ylabel('Y axis')
 plt.title('2d Diagram')
 plt.legend(['y-values']);
```
![image](https://github.com/user-attachments/assets/489479a3-8d42-4bc8-a247-23ac8917a242)
```
 x=np.arange(0,4*np.pi,0.1)
 y=np.sin(x)
 plt.title("sine wave form")
 plt.plot(x,y)
 plt.show()
```
![image](https://github.com/user-attachments/assets/08e78941-edc2-4b2b-9576-24cbdb67e7e3)
```
 import matplotlib.pyplot as plt
 import numpy as np
 x=[1,2,3,4,5]
 y1=[10,12,14,16,18]
 y2=[5,7,9,11,13]
 y3=[2,4,6,8,10]
 plt.fill_between(x,y1,color='blue')
 plt.fill_between(x,y2,color='green')
```
![image](https://github.com/user-attachments/assets/cc75fa9d-6389-4848-a498-1c7c27fa42ed)
```
 import matplotlib.pyplot as plt
 import numpy as np
 x=[1,2,3,4,5]
 y1=[10,12,14,16,18]
 y2=[5,7,9,11,13]
 y3=[2,4,6,8,10]
 plt.fill_between(x,y1,color='blue')
 plt.fill_between(x,y2,color='green')
 plt.plot(x,y1,color='red')
 plt.plot(x,y2,color='black')
 plt.legend(['y1','y2'])
 plt.show()
```
![image](https://github.com/user-attachments/assets/864e69cb-1bf1-44f1-be92-1eb1646c67fa)
```
 import matplotlib.pyplot as plt
 height=[10,24,36,40,5]
 names=['one','two','three','four','five']
 c1=['red','green']
 c2=['b','g']
 plt.bar(names,height,width=0.8,color=c1)
 plt.xlabel('x-axis')
 plt.ylabel('y-axis')
 plt.title('My bar chart!')
 plt.show()
```
![image](https://github.com/user-attachments/assets/0e1539f9-b1e8-45a4-af4b-ac4c458c0a52)
```
 x=[2,8,10]
 y=[11,16,9]
 x2=[3,9,11]
 y2=[6,15,7]
 plt.bar(x,y,color='r')
 plt.bar(x2,y2,color='g')
 plt.title('Bar graph')
 plt.ylabel('Y axis')
 plt.xlabel('X axis')
 plt.show()
```
![image](https://github.com/user-attachments/assets/76a7d748-3d77-4fa4-bfb7-36c3c3491f4a)
```
 import matplotlib.pyplot as plt
 ages=[2,5,70,40,30,45,50,45,43,40,44,60,7,13,57,18,90,77,32,21,20,40]
 range=(0,100)
 bins=10
 plt.hist(ages,bins,range,color='green',histtype='bar',rwidth=0.8)
 plt.xlabel('age')
 plt.ylabel('No. of people')
 plt.title('My histogram')
 plt.show()
```
![image](https://github.com/user-attachments/assets/215413a1-919f-432b-bdfa-a44a3d611ca0)
```
 import matplotlib.pyplot as plt
 import numpy as np
 np.random.seed(0)
 data=np.random.normal(loc=0,scale=1,size=100)
 data
```
![image](https://github.com/user-attachments/assets/7027f24b-bfe7-4e8b-af7b-aa98fc3359eb)
```
 fig,ax=plt.subplots()
 ax.boxplot(data)
 ax.set_xlabel('Data')
 ax.set_ylabel('Values')
 ax.set_title('Box Plot')
```
![image](https://github.com/user-attachments/assets/63b45ae3-4251-4e5d-8287-bccfd0882e7c)
```
labels='Python','C++','Ruby','Java'
sizes=[215,130,245,210]
colors=['gold','yellowgreen','lightcoral','lightskyblue']
explode=(0,0.4,0,0.5)
plt.pie(sizes,explode=explode,labels=labels,colors=colors,autopct='%1.1f%%',shadow=True)
plt.axis('equal')
plt.show()
```
![image](https://github.com/user-attachments/assets/2d665477-669f-4d1b-a216-3ee722c9e96f)
```
activities=['eat','sleep','work','play']
slices=[3,7,8,6]
colors=['r','y','g','b']
plt.pie(slices,labels=activities,colors=colors,startangle=90,shadow=True,explode=(0,0,0.1,0),radius=1.2,autopct='%1.1f%%')
plt.legend()
```
![image](https://github.com/user-attachments/assets/158a0b4a-9348-4589-9eee-8da12c08dfd2)


# Result:
Thus, the Data Visualization using matplot python library for the given datas is performed.
