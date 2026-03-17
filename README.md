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

Name : Lakshanya.N
Reg no : 212224230136

```
import matplotlib.pyplot as plt
x_values=[0,1,2,3,4,5]
y_values=[0,1,4,9,16,25]
plt.plot(x_values,y_values)
plt.show()
```
![image](https://github.com/user-attachments/assets/f02b7eb9-5dee-43eb-a478-e942e9fb01fe)

```
x=[1,2,3]
y=[2,4,1]
plt.plot(x,y)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My first graph')
plt.show()
```
![image](https://github.com/user-attachments/assets/2d17f719-a298-4b32-87da-b2429f5a9a0a)

```
x1=[1,2,3]
y1=[2,4,1]
plt.plot(x1,y1,label="line 1")
x2=[1,2,3]
y2=[4,1,3]
plt.plot(x2,y2,label="line 2")
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Two lines on same graph')
plt.legend()
plt.show()
```
![image](https://github.com/user-attachments/assets/641d3bcb-e9a9-4adc-aaa0-a8446cbaec9c)

```
x=[1,2,3,4,5,6]
y=[2,4,1,5,2,6]
plt.plot(x,y,color='green',linestyle='dashed',linewidth=3,marker='o',markerfacecolor='blue') # Added closing quote and a color 'blue'
plt.ylim(1,8)
plt.xlim(1,8)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Some cool customizations')
plt.show()
```
![image](https://github.com/user-attachments/assets/6d5a0892-a544-40f2-81bc-5a0e0e2cd1a4)

```
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(yield_apples)
```
![image](https://github.com/user-attachments/assets/77922832-01e6-4564-9442-192855289bf1)

```
years=[2010,2011,2012,2013,2014,2015]
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yield_apples)
```
![image](https://github.com/user-attachments/assets/a85d3f2d-03e5-43d3-884b-0b05b115a1cd)

```
years=range(2000,2012)
apples=[0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9375,0.895] 
oranges=[0.962,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.895] 
plt.plot(years , apples)
plt.plot(years,oranges)
plt.xlabel('Year')
plt.ylabel('Yield(tons per hectare)');
```
![image](https://github.com/user-attachments/assets/f6e945a7-defa-4310-9ff4-56eda03b6c75)

```
plt.plot(years,apples)
plt.plot(years,oranges)
plt.xlabel('Year')
plt.ylabel('Yield(tons per hectare)')
plt.title("Crop yield in Kanto")
plt.legend(['Apples','Oranges'])
```
![image](https://github.com/user-attachments/assets/2b6d5c92-7ce1-4639-ba2e-13d2023ea312)

```
years=[2010,2011,2012,2013,2014,2015]
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yield_apples)
plt.xlabel('Year')
plt.ylabel('Yield(tons per hectare)');
```
![image](https://github.com/user-attachments/assets/353e554d-5349-47cb-b694-13e1fdc282b4)

```
plt.figure(figsize=(12,6))
years=range(2000,2012)
plt.plot(years,oranges,marker='o')
plt.title("Yield of oranges (tons per hectare)");
```
![image](https://github.com/user-attachments/assets/9ac67091-d7e5-40d0-9258-397a139b5d3c)

```
plt.plot(years,apples,marker='o')
plt.plot(years,oranges,marker='x')
plt.xlabel('Year')
plt.ylabel('Yield (tons per hectare)')
plt.title("Crop Yields in kanto")
plt.legend(['Apples','Oranges'])
```
![image](https://github.com/user-attachments/assets/646bd07b-9efb-4052-abfd-a6f8c6a8afcb)

```
import matplotlib.pyplot as plt
x_values=[0,1,2,3,4,5]
y_values=[0,1,4,9,16,25]
plt.scatter(x_values,y_values,s=30,color="blue")
plt.show()
```
![image](https://github.com/user-attachments/assets/8a5c23e0-2bc1-4c21-bbfe-6eb77dd5eabd)

```
import matplotlib.pyplot as plt
x=[1,2,3,4,5,6,7,8,9,10]
y=[2,4,5,7,6,8,9,11,12,12]
plt.scatter(x,y,label="stars",color="green",marker="*",s=30)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My scatter plot!')
plt.legend()
plt.show()
```
![image](https://github.com/user-attachments/assets/54bf5c7b-cb8c-4d18-8e1b-0951c282f521)

```
import numpy as np
x=np.arange(0,10)
y=np.arange(11,21)
x
```
![image](https://github.com/user-attachments/assets/f6cb0bfa-e435-4384-9e22-dea384032cf1)

```
y
```
![image](https://github.com/user-attachments/assets/184443b3-a326-459f-8db9-cae10bc60ea8)

```
plt.scatter(x,y,c='r')
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('Graph in 2D')
plt.savefig('Test.png')
```
![image](https://github.com/user-attachments/assets/24e184cb-7440-4b22-8e0f-01562fd4c5e1)

```
y=x*x
y
```
![image](https://github.com/user-attachments/assets/b9596a81-1900-415b-afc2-d11d7ce83c40)

```
plt.plot(x,y,'g*',linestyle='dashed',linewidth=2,markersize=12)
plt.xlabel('x axis')
plt.ylabel('Y axis')
plt.title('2d Diagram')
```
![image](https://github.com/user-attachments/assets/4b2ab289-8ee1-480f-ae4b-4ba54273e020)

```
plt.subplot(2,2,1)
plt.plot(x,y,'r--')
plt.subplot(2,2,2)
plt.plot(x,y,'g*--')
plt.subplot(2,2,3)
plt.plot(x,y,'bo')
plt.subplot(2,2,4)
plt.plot(x,y,'go')
```
![image](https://github.com/user-attachments/assets/9eef89c6-a996-434d-bbbb-0ab7f893cf57)

```
np.pi
```
![image](https://github.com/user-attachments/assets/bba420a0-cb56-42bf-9648-0a4d3fedc857)

```
x=np.arange(0,4*np.pi,0.1)
y=np.sin(x)
plt.title("sine wave form")
plt.plot(x,y)
plt.show()
```
![image](https://github.com/user-attachments/assets/a9026c9b-69a7-417f-8e99-3693859e37b7)

```
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
![image](https://github.com/user-attachments/assets/fae028f4-dd38-43c1-a491-77970cf91b28)

```
plt.stackplot(x,y1,y2,y3,labels=['Line 1','Line 2','Line 3'])
plt.legend(loc='upper left')
plt.title('Stacked Line Chart')
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.show()
```
![image](https://github.com/user-attachments/assets/607bfd3d-98e6-49d0-bb0a-b81107c1ab9f)

```
import numpy as np
import matplotlib.pyplot as plt
from scipy.interpolate import make_interp_spline
x=np.array([1,2,3,4,5,6,7,8,9,10])
y=np.array([2,4,5,7,8,8,9,10,11,12])
spl=make_interp_spline(x,y)
x_smooth=np.linspace(x.min(),x.max(),100)
y_smooth=spl(x_smooth)
plt.plot(x,y,'o',label='data')
plt.plot(x_smooth,y_smooth,'-',label='Spline')
plt.legend()
plt.show()
```
![image](https://github.com/user-attachments/assets/904d2d92-d78c-4b2a-aa56-786ea118eec0)

```
import matplotlib.pyplot as plt
values=[5,6,3,7,2]
names=["A","B","C","D","E"]
plt.bar(names,values,color="green")
plt.show()
```
![image](https://github.com/user-attachments/assets/2711c38f-3a15-4152-9fa3-f85be76a3e2c)

```
values=[5,6,3,7,2]
names=["A","B","C","D","E"]
plt.barh(names,values,color="yellowgreen")
plt.show()
```
![image](https://github.com/user-attachments/assets/2dc9fe43-edbe-4564-bb39-04d31d935fba)

```
height=[10,24,36,40,5]
names=['one','two','three','four','five']
c1=['red','green']
c2=['b','g']
plt.bar(names,height,width=0.8,color=c1)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My Bar Chart!')
plt.show()
```
![image](https://github.com/user-attachments/assets/c783d857-5a2f-4651-a2ef-1584650c200a)

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
![image](https://github.com/user-attachments/assets/10362787-3690-4ec9-841e-e5b395a6b970)

```
ages=[2,5,70,40,30,45,50,45,43,40,44,60,7,13,57,18,90,77,32,21,20,40]
range=(0,100)
bins=10
plt.hist(ages,bins,range,color='green',histtype='bar',rwidth=0.8)
plt.xlabel('age')
plt.ylabel('No. of people')
plt.title('My histogram')
plt.show()
```
![image](https://github.com/user-attachments/assets/d562442f-d3ce-4341-bdd3-c4da27698536)

```
x=[2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x,bins=10,color='blue',alpha=0.5)
plt.show()
```
![image](https://github.com/user-attachments/assets/a279dee9-33db-44e5-9484-f8a50522db4c)

```
import numpy as np
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data
```
![image](https://github.com/user-attachments/assets/69ad354f-3e13-4266-915d-2e4c17ee22c8)

```
fig,ax=plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Value')
ax.set_title('Box Plot')
```
![image](https://github.com/user-attachments/assets/50ae528e-2967-4260-abae-cedc32a9488c)

```
activities=['eat','sleep','work','play']
slices=[3,7,8,6]
colors=['r','g','b','y']
plt.pie(slices,labels=activities,colors=colors,startangle=90,shadow=True,explode = (0, 0.1, 0, 0))
plt.legend()
plt.show()
```
![image](https://github.com/user-attachments/assets/4429de9b-855a-491a-9253-609cc00edf60)

```
labels='Python','C++','Ruby','Java'
sizes=[215,130,245,210]
colors=['gold','yellowgreen','lightcoral','lightskyblue']
explode=(0,0.4,0,0.5)
plt.pie(sizes,explode=explode,labels=labels,colors=colors,autopct='%1.1f%%') # Added closing parenthesis
plt.axis('equal')
plt.show()
```
![image](https://github.com/user-attachments/assets/7ab24a7c-1305-44db-9e37-e38209466811)

```

# Result:
    Data Visualization using matplot python library for the given datas has been performed
 successfully.
