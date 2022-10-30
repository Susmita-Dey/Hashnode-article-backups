# Variables and Datatypes in Python

# Variables
As the name suggests, variables means something that can vary. That means, something that can be changed.      
Let's take a real-world example to make you understand. 

![Mixing ingredients - variables.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1645269986806/6YNJcTHZF.png)

In this image, you can see that there are two bowls containing some ingredients in it. And after some time a person is adding the items from the bowls into another single one in order to mix them. So, here gradually the value of the two bowls are decreasing and the value of the 3rd bowl is increasing. That means, in general, the amount of ingredients in the respective bowls are changing. So, here you can call  each bowl as a **variable** and the items present in each of them as their **value**.

By this, you might have got some idea of variables and their values.  

---
## Declaring and Initializing Python Variables
Now, let's see an example of python to demonstrate variables.
```python
a = 5
b = 6
c = 3
```
Here, you can see I have declared 3 variables named a, b and c. I've assigned them with values 5, 6 and 3 respectively.        
So, this is the way of declaring and initializing variables in python.      

📝**Note that you cannot declare a variable and leave it without initializing it.**    
For example - 
```python
a, b = 5
```
Here, a is invalid and will give an error.

---
### Multiple Assignment of Variables
You can assign multiple variables will the same value together in the following way.
```python
a = b = c = 5
```
You can also assign multiple variables with different values together in a serial order.   
For example:- 
```python
a, b, c = 5, 6, 7
```
Here, value of a is 5, value of b is 6 and value of c is 7.

---
## 💡 Naming Convention of Variables in Python
1. Variables should start with alphabets or with an underscore followed by alphabets.
For example:- `_var` or `var_one` or 
2. You can use _(underscore) and numbers to name your variables.     
For example:- `name_1`
3. They should not contain any white-space or special characters like e.g. & (ampersand), $ (dollar).
4. If you want to give your variables a big name, then you can use underscores (_) to separate the words.    
   For example:- `json_string`
5. Variable names are case sensitive in Python.      
For example:- `age` and `Age` are two different variables.
6. You can use camelCase to name your variable.       
For example:- `myName`
7. There are some reserved keywords in Python. Those keywords are already taken by the people who have made Python. So, don't use those keyword as a variable name otherwise python will become confused and it will throw errors.    
Some of those keywords are:-  if, else, elif, range, class, for, def, del, is, try, from, while, etc.
There are many of them. You'll learn about them gradually.

---
## 📒 Variable Object Reference
Python is a high-level interpreted language. So, it treats every item as an object.
For example:-
You have assigned two variables a and b with the same value, say, 5.
Now, 5 is an object located at a certain place in your computer's memory having a memory address and the two variables are acting as pointers pointing to the object.

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1645276177880/XgeHV1onC.png)

Not only in this case, but in every case, i.e., whenever to declare and initialize a variable, the value assigned to it becomes an object and each variable points to their respective object value located at some point in the memory.

---
### Checking the type of object
You can check the type of object by using type() function in Python.
```python
a = 6
print(type(a))
```
This code snippet will return the following output - 
```python
<class 'int'>
```
This is because 6 is a number and is of type integer.
Here, type() function is an in-built function in Python which is used to analyze the type of object.

Let's take another example.
```python
name = "Susmita"
print(type(name))
```
This code snippet will return the following output - 
```python
<class 'str'>
```
This is because Susmita is a name of a person and is of type string.

---
## Identity of Objects
In Python, every every created object has an unique identity. Python provides every object different identity number and also ensures that no two object have the same identity.     
We use id() function to identify the object identifier. It is a built-in function in Python. 
For example:- 
```python
age = 18
name = "Susmita"
print(id(name))
print(id(age))
```
This should give some random unique numbers as follows - 
![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1645277593132/WBNLfFGAQ.png)
Here, you can see both the id's are different.

Let's see another example - 
```python
age = "Susmita"
name = "Susmita"
print(id(name))
print(id(age))
```
This would return some random id both having the same values as follows.
![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1645277553091/j5hGr7Aiga.png)

Now, you might feel confused. 😵
So, let me explain. In the last example we've taken two variables having the same values called Susmita. Since python treats the values as objects and assigns the unique id to the objects and not to the variables and the variables act as pointers pointing to the object, so its obvious that the code snippet will return same values.
Hope, this clears your confusion. 

*<iframe src="https://giphy.com/embed/hVYVYZZBgF50k" width="280" height="280" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/daughter-houston-bathtub-hVYVYZZBgF50k">GIF source is via GIPHY</a></p>*

---
# Data Types

Some of the basic datatypes in Python are -
1. Integer(int)
2. Floating Point(float)
3. Strings(str)
4. Boolean(bool)

In order to know the datatype of a variable after assigning some value to it, we use `type()` function.

---
## 1. Integer Data Type
By the term integer, we often understand that it can either be a negative or a positive number or zero. 
```python
a = 6
b = -77
``` 
Here, a and b both are integer datatypes as they contain integer values(one positive, one negative).
Let's check it's datatype to get sure.
```python
a = 6
print(type(a))
``` 
**Output:-**
![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1647169950485/02ddVQQX3.png)

---
## 2. Float Data Type
By the term float, we often understand that it can either be a negative or a positive decimal number. 
```python
a = 6.98
b = -77.56
``` 
Here, a and b both are float data types as they contain floating point values(one positive, one negative).
Let's check it's datatype to get sure.
```python
a = 7.7
print(type(a))
``` 
**Output:-**
![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1647170243251/aAH68bUn0.png)

---
## 3. String Data Type
By the term string, we often understand that it can be a word or a sentence or a paragraph. 
```python
a = 'Hello'
b = "I am Python"
``` 
Here, a and b both are string data types as they contain Strings. 
Let's check it's datatype to get sure.
```python
a = 'Hello'
print(type(a))
``` 
**Output:-**
![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1647170451073/SYn0M4X9M.png)
```python
b = "I am Python"
print(type(b))
``` 
**Output:-**
![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1647170451073/SYn0M4X9M.png)

**Note:-** You can denote strings in both ways(either using '' or using "" ) as you like. But some important things you should keep in mind.

Check out the following examples -
```python
a = '55'
print(type(a))
``` 
**Output:-**
![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1647170451073/SYn0M4X9M.png)
This is a string because we have written 55 inside *single quotation marks* and then assigned to variable a. 

```python
a = "I'm Susmita"
print(type(a))
``` 
**Output:-**
![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1647170451073/SYn0M4X9M.png)
Here, you can see I have used *double quotes* to write the sentence. I can obviously use here single quotes but in this particular case it will give me error if I do so. Since, I haven't done it, so my program is working perfectly without any error.

Now, your question might be why it will give error?

Let's do that and run the program to see the output.
```python
a = 'I'm Susmita'        # wrong code
print(type(a))
``` 
**Output:-**
![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1647171082524/EJh9Oq7rZ.png)
It is because in the sentence I have written `I'm` and as you can write strings using `''`, so when you're writing `I` and then using `'` after that then it closes the string here and then it detects a string to be started after Susmita is written. So, this gives syntax error.                                                                 
I hope it is clear to you now.

There are some more parts of strings and we'll go deep dive into it later on when we will deal with Strings chapter.

---
## 4. Boolean Data Type
By the term float, we often understand that it can either be a `True` value or a `False` value. 
```python
a = True
b = False
``` 
Here, a and b both are boolean data types as they contain boolean values.
Let's check it's datatype to get sure.
```python
a = True
print(type(a))
``` 
**Output:-**
![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1647171817165/Qj9lAOH7Y.png)

So, this was the overall basics of understanding data types. There are some other data types in Python. We'll discuss them later in detail.

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1647172032004/i6QfV8GH-.png)
> Picture by [GeeksForGeeks](https://www.geeksforgeeks.org)

---

# Hope this helps you. Thank you for reading, and let's connect!
Thank you for reading my blog. Feel free to subscribe to my [YouTube Channel](https://www.youtube.com/channel/UCsuzc8lqAbgUYo4yzpjtfSw) and connect on [LinkedIn](https://www.linkedin.com/in/susmita-dey-15a15a210/) or [Twitter](https://twitter.com/its_SusmitaDey).
Also, feel free to [support](https://www.buymeacoffee.com/susmitadey) my work.😊