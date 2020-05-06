#!/usr/bin/env python
# coding: utf-8

# In[7]:




# ### Que 1

# In[1]:


class triangle:
    def create_triangle():
        
    def print_sides():
        
        
    


# ### Que 2

# In[4]:


a = " "
class que2:
    def inputstr():
        a = input("Enter a string");
        
    def printstr(a):
        print(a)
        
        
que2.inputstr()
que2.printstr(a)


# ### Que 3

# In[5]:


class rectangle():
    def __init__(self,breadth,length):
        self.breadth=breadth
        self.length=length
    def area(self):
        return self.breadth*self.length
a=int(input("Enter length of rectangle: "))
b=int(input("Enter breadth of rectangle: "))
obj=rectangle(a,b)
print("Area of rectangle:",obj.area())
 
print()


# ### Que 4

# In[6]:


import math
class circle():
    def __init__(self,radius):
        self.radius=radius
    def area(self):
        return math.pi*(self.radius**2)
    def perimeter(self):
        return 2*math.pi*self.radius
 
r=int(input("Enter radius of circle: "))
obj=circle(r)
print("Area of circle:",round(obj.area(),2))
print("Perimeter of circle:",round(obj.perimeter(),2))


# ### Que 5

# In[ ]:


Class Base1:
       Body of the class

Class Base2:
     Body of the class

Class Derived(Base1, Base2):
     Body of the class

