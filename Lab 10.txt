#!/usr/bin/env python
# coding: utf-8

# ## LAB 10



# In[1]:


class MyClass:
    "This is my second class"
    a = 10
    def func(self):
        print('Hello')

print(MyClass.a)

print(MyClass.func)

print(MyClass.__doc__)


# ### Que 4

# In[2]:


class Parent(): 
      
    # Constructor 
    def __init__(self): 
        self.value = "Inside Parent"
          
    # Parent's show method 
    def show(self): 
        print(self.value) 
          
# Defining child class 
class Child(Parent): 
      
    # Constructor 
    def __init__(self): 
        self.value = "Inside Child"
          
    # Child's show method 
    def show(self): 
        print(self.value) 
           
obj1 = Parent() 
obj2 = Child() 
  
obj1.show() 
obj2.show() 


# ### Que 5

# In[3]:


class Class1: 
    def m(self): 
        print("In Class1")  
        
class Class2(Class1): 
    def m(self): 
        print("In Class2") 
  
class Class3(Class1): 
    def m(self): 
         print("In Class3")      
      
class Class4(Class2, Class3): 
    def m(self): 
        print("In Class4")    
  
obj = Class4() 
obj.m() 
  
Class2.m(obj) 
Class3.m(obj) 
Class1.m(obj)


# In[ ]:




