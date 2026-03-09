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

%matplotlib inline
import numpy as np
## Simple Examples

x=np.arange(1,11)
y=np.arange(12,22)
a=np.arange(50,60)
b=np.arange(60,70)
##plotting using matplotlib 

##plt scatter

plt.scatter(x,y,c='b')
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('Graph in 2D')
plt.savefig('Test.png')
y=x*x
## plt plot

plt.plot(x,y,'g*',linestyle='dashed',linewidth=2, markersize=12)
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('2d Diagram')
plt.show()
## Creating Subplots

plt.subplot(2,2,1)
plt.plot(x,y,'g-')
plt.subplot(2,2,2)
plt.plot(x,y,'r*--')
plt.subplot(2,2,3)
plt.plot(x,y,'yo')
plt.subplot(2,2,4)
plt.plot(x,y,'bo')
plt.show()
x = np.arange(0,10) 
y = 3 * x + 5 
plt.title("Matplotlib demo") 
plt.xlabel("x axis caption") 
plt.ylabel("y axis caption") 
plt.plot(x,y) 
plt.show()
np.pi
# Compute the x and y coordinates for points on a sine curve 
x = np.arange(0, 4 * np.pi, 0.1) 
y = np.cos(x) 
plt.title("cosine wave form") 

# Plot the points using matplotlib 
plt.plot(x, y) 
plt.show() 
#Subplot()
# Compute the x and y coordinates for points on sine and cosine curves 
x = np.arange(0, 5 * np.pi, 0.1) 
y_sin = np.sin(x) 
y_cos = np.cos(x)  
   
# Set up a subplot grid that has height 2 and width 1, 
# and set the first such subplot as active. 
plt.subplot(2, 1, 1)
   
# Make the first plot 
plt.plot(x, y_sin,'g*--') 
plt.title('Sine')  
   
# Set the second subplot as active, and make the second plot. 
plt.subplot(2, 1, 2) 
plt.plot(x, y_cos,'r*--') 
plt.title('Cosine')  
   
# Show the figure. 
plt.show()
## Bar plot

x = [4,8,12] 
y = [5,10,15]  

x2 = [3,9,11] 
y2 = [6,15,7] 
plt.bar(x, y) 
plt.bar(x2, y2, color = 'g') 
plt.title('Bar graph') 
plt.ylabel('Y axis') 
plt.xlabel('X axis')  

plt.show()
a = np.array([22,85,5,43,56,7,52,54,11,20,51,5,79,35,20]) 
plt.hist(a) 
plt.title("histogram") 
plt.show()
data = [np.random.normal(0, std, 100) for std in range(1, 5)]

# rectangular box plot
plt.boxplot(data,vert=True,patch_artist=False);  
plt.show()
data = [np.random.normal(0, std, 100) for std in range(1, 5)]

# rectangular box plot
plt.boxplot(data,vert=True,patch_artist=True);
plt.show() 
data
# Data to plot
labels = 'Python', 'C++', 'Ruby', 'Java'
sizes = [215, 130, 245, 210]
colors = ['red', 'lightskyblue', 'pink', 'yellowgreen']
explode = (0.1, 0.1, 0.1, 0.1)  # explode 1st slice

# Plot
plt.pie(sizes, explode=explode, labels=labels, colors=colors,
autopct='%1.1f%%', shadow=False)

plt.axis('equal')
plt.show()


<img width="1919" height="1078" alt="image" src="https://github.com/user-attachments/assets/9832a01f-629b-4994-a2ea-2dcc8aee0601" />

<img width="1918" height="1068" alt="image" src="https://github.com/user-attachments/assets/ee49fd24-74c0-4147-88da-7d1068ad38fd" />

<img width="1917" height="1067" alt="image" src="https://github.com/user-attachments/assets/0afd7679-7046-401e-9a8e-9c27cce0ce5b" />

<img width="1919" height="1067" alt="image" src="https://github.com/user-attachments/assets/b318a69b-e602-4372-90f3-f8056c5091ad" />

<img width="1906" height="1056" alt="image" src="https://github.com/user-attachments/assets/865877a6-f166-41dd-8e02-6b8cba8a062a" />

<img width="1919" height="1068" alt="image" src="https://github.com/user-attachments/assets/654930a9-ad1e-4e77-945d-d351eca50a10" />

<img width="1919" height="1065" alt="image" src="https://github.com/user-attachments/assets/c573ba5f-1959-44a8-81c9-a0b1f8b1084d" />

<img width="1916" height="1073" alt="image" src="https://github.com/user-attachments/assets/9dfdf5ab-8e7a-412e-b82a-9b3feb400c9a" />

<img width="1908" height="1063" alt="image" src="https://github.com/user-attachments/assets/b3e04323-b2ba-42ed-b536-c473bb210619" />

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/d4900cf1-7046-4f6a-b703-ce0ef2845ed7" />

<img width="1917" height="1079" alt="image" src="https://github.com/user-attachments/assets/833f6d29-5acd-4a18-b20e-96cfeb3a093c" />

[vertopal.com_Matplotlib.pdf](https://github.com/user-attachments/files/25833606/vertopal.com_Matplotlib.pdf)








# Result:
Hence, the given task To Perform Data Visualization using matplot python library for the given datas has been done successfully. 
