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
x_val = [0,1,2,3,4,5]
y_val = [0,1,4,9,16,25]
plt.plot(x_val,y_val)
plt.show()
```
![325700663-7ea276da-329c-4e1b-af27-3ccbc2e158e8](https://github.com/aparnabalasubrmanian/EXNO-5-DS/assets/123351172/c3b1567c-eda6-46f9-97c0-5edcbc751613)
```
import matplotlib.pyplot as plt
x = [1,2,3]
y = [2,4,1]
plt.plot(x,y)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My first graph')
plt.show()
```
![325700892-53f92332-e90c-481d-b3db-b3a8b253211b](https://github.com/aparnabalasubrmanian/EXNO-5-DS/assets/123351172/0e9fe2e2-0d99-4f7e-bdb7-85543ac9252b)
```
import matplotlib.pyplot as plt
x1 = [1,2,3]
y1 = [2,5,3]
plt.plot(x1,y1,label = 'line 1')
x2 = [1,2,3]
y2 = [3,1,6]
plt.plot(x2,y2,label = 'line 2')
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title("Two lines on the same graph")
plt.legend()
plt.show()
```
![325701123-2cc396f0-67ac-4526-9301-1126cb6eb146](https://github.com/aparnabalasubrmanian/EXNO-5-DS/assets/123351172/7678c654-4c38-4d56-9739-82c396ee8ada)
```
import matplotlib.pyplot as plt
import numpy as np
x = [1,2,3,4,5]
y1 = [10,12,14,16,18]
y2 = [5,7,9,11,13]
y3 = [2,4,6,8,10]
plt.fill_between(x,y1,color = 'blue')
plt.fill_between(x,y2,color = 'orange')
```
![325701443-12d2d32e-2a72-4864-aeec-89af7b2f681d](https://github.com/aparnabalasubrmanian/EXNO-5-DS/assets/123351172/73207267-25b7-4d47-8ddc-8de6c259faa8)
```
plt.stackplot(x,y1,y2,y3,labels = ['line1','line2','line3'])
plt.legend(loc = 'upper left')
plt.title('Stacked line charts')
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.show()
```
![325701633-676db96f-5e9c-4ee4-a139-d42346831da8](https://github.com/aparnabalasubrmanian/EXNO-5-DS/assets/123351172/85a5c274-6f3c-4644-916f-8911a32ab070)
```
import numpy as np
import matplotlib.pyplot as plt
val = [2,4,7,3]
names = ['A','B','C','D']
plt.bar(names, val,color = 'purple')
plt.show()
```
![325701778-7d71481a-1aa6-4b57-a5af-95af9b12a4be](https://github.com/aparnabalasubrmanian/EXNO-5-DS/assets/123351172/bbef76a4-0018-454e-81af-c4c29f91cc01)
```
import matplotlib.pyplot as plt
import numpy as np
ages = [2,6,4,12,13,12,16,18,18,19,26,24,39,34,45,42,54,56,90,56,86,79]
range = (0,100)
bins = 10
plt.hist(ages,bins,range,color='green',histtype='bar',rwidth=0.8)
plt.xlabel('age')
plt.ylabel('no of people')
plt.title('histogram')
plt.show()
```
![325701999-5b088d34-b1ee-4b3e-a229-39360d583bf6](https://github.com/aparnabalasubrmanian/EXNO-5-DS/assets/123351172/45c9d44d-536f-4d4b-a30a-a1556a5e4762)
```
import matplotlib.pyplot as plt
import numpy as np
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data
```
![325702341-d66d7f36-ff0d-41de-9fdd-1ebd34f79828](https://github.com/aparnabalasubrmanian/EXNO-5-DS/assets/123351172/57013638-cf5c-4384-807d-a5ae720fac62)
```
fig,ax=plt.subplots()
ax.boxplot(data)
ax.set_xlabel("data")
ax.set_ylabel("values")
ax.set_title("box plot")
```
![325702521-4cdf0d14-c240-4e56-9ef1-ed0ac3eef7d2](https://github.com/aparnabalasubrmanian/EXNO-5-DS/assets/123351172/c1307c5c-99e4-4e67-b0a0-2a59ef9eecc6)
```
import matplotlib.pyplot as plt
activities=['eat','sleep','work','play']
slices=[3,7,8,6]
colors=['r','y','g','b']
plt.pie(slices,labels = slices,colors=colors,startangle=90,shadow = True,explode = (0,0,0.1,0),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
```
![325702693-ddb35914-91b3-478a-81cf-f76e9cc9c071](https://github.com/aparnabalasubrmanian/EXNO-5-DS/assets/123351172/aff6791e-db9d-4bff-8f4a-6ee9444d5913)

# Result:
  Thus, We have successfullu performed Data Visualization using matplot python library for the given datas.
