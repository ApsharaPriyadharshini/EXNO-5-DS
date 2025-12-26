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
import matplotlib.pyplot as plt
x_values=[0,1,2,3,4,5]
y_values=[0,1,4,9,16,25]
plt.plot(x_values,y_values)
plt.show()

<img width="1247" height="531" alt="image" src="https://github.com/user-attachments/assets/d09ace65-d726-4405-9d4d-fea7bc7727f4" />

import matplotlib.pyplot as plt
x=[1,2,3]
y=[2,4,1]
plt.plot(x,y)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My first graph!')
plt.show()

<img width="1259" height="588" alt="image" src="https://github.com/user-attachments/assets/418d1310-5a84-4908-89c0-18b52ab3d72f" />

import matplotlib.pyplot as plt
x1=[1,2,3]
y1=[2,4,1]
plt.plot(x1,y1,label="line 1")
x2=[1,2,3]
y2=[4,1,3]
plt.plot(x2,y2,label="line 2")
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title("Two lines on same graph!")
plt.legend()
plt.show()

<img width="1244" height="589" alt="image" src="https://github.com/user-attachments/assets/3ef627e4-e697-46b5-8f78-3c435e22c441" />

import matplotlib.pyplot as plt
x=[1,2,3,4,5,6]
y=[2,4,1,5,2,6]
plt.plot(x,y,color='green',linestyle='dashed',linewidth=3,marker='o',markerfacecolor='blue',markersize=12)
plt.ylim(1,8)
plt.xlim(1,8)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Some cool customiztions!')
plt.show()

<img width="1250" height="583" alt="image" src="https://github.com/user-attachments/assets/ec8ce0c7-5f52-4db1-917a-6ddfc0da2c1f" />

yield_apples=[0.89589,0.91,0.919,0.926,0.929,0.931]
plt.plot(yield_apples)

<img width="1259" height="574" alt="image" src="https://github.com/user-attachments/assets/0d6b2ef3-2de8-4ac2-a3b2-a20e35216ab1" />

years=[2010,2011,2012,2013,2014,2015]
yiels_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yield_apples)

<img width="1256" height="579" alt="image" src="https://github.com/user-attachments/assets/486a492f-03af-433e-9310-c337f9068071" />

years=range(2000,2012)
apples=[0.894,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
oranges=[0.962,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896,]
plt.plot(years, apples)
plt.plot(years, oranges)
plt.xlabel('Year')
plt.ylabel('Yield (tons per hectare)');

<img width="1257" height="557" alt="image" src="https://github.com/user-attachments/assets/d7552cc6-b8f8-4ede-afad-e6ae26580bf5" />

plt.plot(years,apples)
plt.plot(years,oranges)
plt.xlabel('Year')
plt.ylabel('Yiels (tons per hectare)')
plt.title("Crop yields in Kanto")
plt.legend(['Apples','Oranges']);

<img width="1251" height="582" alt="image" src="https://github.com/user-attachments/assets/ce788dcc-88d3-49cf-b9b2-4e7a144b06f9" />

years=[2010,2011,2012,2013,2014,2015]
yiels_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yield_apples)
plt.xlabel('Year')
plt.ylabel('Yield (tons per hectare)');

<img width="1258" height="561" alt="image" src="https://github.com/user-attachments/assets/13f49075-a06b-4ef4-b952-d4010e42d2e3" />

years=range(2000,2012)
apples=[0.894,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
oranges=[0.962,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896,]
plt.figure(figsize=(12,6))
plt.plot(years,oranges,marker='o')
plt.title("yield of Oranges(tons per hectare)");

<img width="1248" height="670" alt="image" src="https://github.com/user-attachments/assets/b38e578a-0e75-4ae5-b015-d5e73eb2de34" />

plt.plot(years,apples,marker='o')
plt.plot(years,oranges,marker='x')
plt.xlabel('Year')
plt.ylabel('Yield (tons per hectare)')
plt.title("Crop Yields in Kanto")
plt.legend(['Apples','Oranges'])

<img width="1250" height="613" alt="image" src="https://github.com/user-attachments/assets/00ac75c1-f2aa-4170-a8af-23249766610c" />

import matplotlib.pyplot as plt
x_values=[0,1,2,3,4,5]
y_values=[0,1,4,9,16,25]
plt.scatter(x_values,y_values,s=30,color="blue")
plt.show()

<img width="1250" height="536" alt="image" src="https://github.com/user-attachments/assets/0234eba8-ea88-4d58-8afe-42361ccbda2b" />

import matplotlib.pyplot as plt
x=[1,2,3,4,5,6,7,8,9,10]
y=[2,4,5,7,6,8,9,11,12,12]
plt.scatter(x,y,label="stars",color="green",marker="*",s=30)
plt.ylabel('y-axis')
plt.xlabel('x-axis')
plt.title('My scatter plot!')
plt.legend()
plt.show()

<img width="1253" height="586" alt="image" src="https://github.com/user-attachments/assets/02584644-a506-4932-b062-395554395b9e" />

import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
x=np.arange(0,10)
y=np.arange(11,21)
x

<img width="1255" height="44" alt="image" src="https://github.com/user-attachments/assets/7c74d2ae-c515-43a2-a61b-998770ef5a32" />

y

<img width="1243" height="43" alt="image" src="https://github.com/user-attachments/assets/5c6d8ba5-4a68-4b35-8710-4c2dbb225096" />

plt.scatter(x,y,c='r')
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Graph in 2D')
plt.savefig('Test.png')

<img width="1251" height="590" alt="image" src="https://github.com/user-attachments/assets/fa9a90c8-c162-49ba-8782-0cf1097003d3" />

y=x*x
y

<img width="1250" height="45" alt="image" src="https://github.com/user-attachments/assets/9c901d2b-da22-497b-bb58-ad66e9524f93" />

plt.plot(x,y,'g*',linestyle='dashed',linewidth=2,markersize=12)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('2d Diagram')

<img width="1249" height="629" alt="image" src="https://github.com/user-attachments/assets/6e5559fb-b2c2-4f71-9cc7-60866c1afcdb" />

plt.subplot(2,2,1)
plt.plot(x,y,'r--')
plt.subplot(2,2,2)
plt.plot(x,y,'g*--')
plt.subplot(2,2,3)
plt.plot(x,y,'bo')
plt.subplot(2,2,4)
plt.plot(x,y,'go')

<img width="1253" height="580" alt="image" src="https://github.com/user-attachments/assets/bb98e5c4-70a3-4974-8d91-26a16d9a8961" />

np.pi

<img width="1250" height="44" alt="image" src="https://github.com/user-attachments/assets/344d0f79-981e-4a07-b4cc-69779b0eedce" />

x=np.arange(0,4*np.pi,0.1)
y=np.sin(x)
plt.title("Sine wave form")
plt.plot(x,y)
plt.show()

<img width="1248" height="560" alt="image" src="https://github.com/user-attachments/assets/4ccb064b-82b0-4ebd-9f97-d53a6e3b1d2b" />

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

<img width="1263" height="545" alt="image" src="https://github.com/user-attachments/assets/8f3659b4-caaf-46ba-ad34-e05a31bbf1f8" />

plt.stackplot(x,y1,y2,y3 ,labels=['line 2','line 2','line 3'])
plt.legend(loc='upper left')
plt.title('Stacked Line chart')
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.show()

<img width="1257" height="585" alt="image" src="https://github.com/user-attachments/assets/d0c83036-2c36-45c5-badb-acc106182293" />

import numpy as np
import matplotlib.pyplot as plt
from scipy.interpolate import make_interp_spline
x=np.array([1,2,3,4,5,6,7,8,9,10])
y=np.array([2,4,5,7,8,8,9,10,11,12])
spl=make_interp_spline(x,y)
x_smooth=np.linspace(x.min(),x.max(),100)
y_smooth=spl(x_smooth)
plt.plot(x,y,'o',label='data')
plt.plot(x_smooth,y_smooth,'-',label='spline')
plt.legend()
plt.show()

<img width="1253" height="537" alt="image" src="https://github.com/user-attachments/assets/6d8c1fd4-99f1-4dc7-9a19-5c815fcbf854" />

import matplotlib.pyplot as plt
values=[5,6,3,7,2]
names=["A","B","C","D","E"]
plt.bar(names,values,color="green")
plt.show()

<img width="1247" height="538" alt="image" src="https://github.com/user-attachments/assets/64e8760f-eb6e-4682-819a-b27092695723" />

import matplotlib.pyplot as plt
values=[5,6,3,7,2]
names=["A","B","C","D","E"]
plt.barh(names,values,color="yellowgreen")
plt.show()

<img width="1247" height="539" alt="image" src="https://github.com/user-attachments/assets/5b8e5cea-79e1-4715-9f06-010ee930ea2a" />

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

<img width="1260" height="580" alt="image" src="https://github.com/user-attachments/assets/27d15baa-4521-4693-b207-84cfb0a15107" />

x=[2,8,10]
y=[11,16,9]
x2=[3,9,11]
y2=[6,15,7]
plt.bar(x,y,color='r')
plt.bar(x2,y2,color='g')
plt.ylabel('Y axis')
plt.xlabel('X axis')
plt.show()

<img width="1253" height="561" alt="image" src="https://github.com/user-attachments/assets/78343308-4576-4929-ba77-c05e15d78174" />

import matplotlib.pyplot as plt
ages=[2,5,70,40,30,45,50,45,43,30,44,60,7,13,57,18,90,77,32,21,20,40]
range=(0,100)
bins=10
plt.hist(ages,bins,range,color='green',histtype='bar',rwidth=0.8)
plt.xlabel('age')
plt.ylabel('No.Of.people')
plt.title('My histogram')
plt.show()

<img width="1252" height="581" alt="image" src="https://github.com/user-attachments/assets/0bee8f60-0486-42c1-9adb-7babb0343d6b" />

import matplotlib.pyplot as plt
x=[2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x,bins=10,color='blue',alpha=0.5)
plt.show()

<img width="1248" height="533" alt="image" src="https://github.com/user-attachments/assets/d27cb5e4-0ec6-4677-a69f-a998fa2f9ef7" />

import matplotlib.pyplot as plt
import numpy as np
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data

<img width="1249" height="442" alt="image" src="https://github.com/user-attachments/assets/2f9e60d3-225e-4a0e-9029-fb5682c0efa0" />

fig,ax=plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('values')
ax.set_title('Box plot')

<img width="1252" height="611" alt="image" src="https://github.com/user-attachments/assets/a5ec0b3f-36ee-42ec-8434-8a523bf1120e" />

import matplotlib.pyplot as plt
activities=['eat','sleep','work','play']
slices=[3,7,8,6]
colors=['r','y','g','b']
plt.pie(slices,labels=activities,colors=colors,startangle=90,shadow=True,explode=(0,0,0.1,0),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()

<img width="1248" height="517" alt="image" src="https://github.com/user-attachments/assets/bf53db33-0a84-4ba0-b5bc-567cab0a830d" />

labels='python','c++','Ruby','Java'
sizers=[215,130,245,210]
colors=['gold','yellowgreen','lightcoral','lightskyblue']
explode=(0,0.4,0,0.5)
plt.pie(sizers,explode=explode,labels=labels,colors=colors,autopct='%1.1f%%',shadow=True)
plt.axis('equal')
plt.show()

<img width="1246" height="499" alt="image" src="https://github.com/user-attachments/assets/f61bf50f-b3a2-4421-a730-6b697113f829" />

activities=['eat','sleep','work','play']
slices=[3,7,8,6]
colors=['r','y','g','b']
plt.pie(slices,labels=activities,colors=colors,startangle=90,shadow=True,explode=(0,0,0.1,0),radius=1.2,autopct='%1.1f%%')
plt.legend()


<img width="1253" height="556" alt="image" src="https://github.com/user-attachments/assets/d876120e-82ae-4f1e-8a97-82efbaec584f" />








# Result:
 Thus, Data visualization usinf Matplotlib is executed successfully and the output is verified.
