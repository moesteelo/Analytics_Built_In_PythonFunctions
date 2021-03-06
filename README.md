# Analytics_Built_In_PythonFunctions
**12 of the most used built in functions data Analytics and Data Scientists use**

## Overview 

### 1) Enumerate Function 
- **The `enumerate()` function allows you to write a for loop that comes with an index. This means we can automatically assign a count variable to each item in an iterable. When we use enumerate(), we get back the count of the current iteration, and then the value of the item at that iteration.Also adding `start` function can start the index from 1 instead of 0**

<img src="img/Enumerate.png">
<img src="img/Enumerate with start.png">

### 2) Sorted Function

- **The `Sorted` function takes an iterable pbject and returns a sorted list of all the items in siad iterable. Strings are sorted alphabetically while numbers are sorted numerically. We can also specify the sorted order by assigning the ***True***** **(descending) or** ***False*** **(ascending) to the reverse arguemnt**

<img src="img/sorted.png">
<img src="img/sorted numbers.png">



### 3) Zip Function

- **The `zip()` function is used to assign items from different iterators together. It returns a zip object, containing tuples of the corresponding items in each iterable.It can also be used together with the built-in dict() function to create a dictionary object.Finally, we can use the zip() function to unpack a series of elements (tuples) in a list to independent tuples by using the * operator.**

<img src="img/zip.png">
<img src="img/zip 1.png">
<img src="img/zip 3.png">

### 4) Map Function

- **The `map()` function takes in another function and an iterable object such as a string or tuple and returns the results after applying the given function to each item in the iterable.** 

<img src= "img/map.png">


### 5) Filter Function

- **Like the map() function, the filter() function also takes in another function and an iterable such as a list or tuple and then returns the elements in the iterable for which the function returns True.**

<img src= "img/map.png">

### 6) InIstance Function

**The `isinstance()` function is used to check if an object is an instance of a specified class. It takes in two arguments, an object and a class name, and then returns True if the object is an instance of that class and False if it???s not.**

<img src= "img/inisntance.png">

### 7) Range Function

- **The `range()` function returns a sequence of numbers with a specified length. It takes in three arguments; start, stop and step. The start argument is optional and specifies the beginning of the sequence, set to 0 by default.The round() function takes in a floating-point number and rounds it up to the nearest integer by default. If specified, the ndigits argument will round up the input to the number of decimal places entered.**

<img src= "img/range.png">

### 8) Round Function

- **The `round()` function takes in a floating-point number and rounds it up to the nearest integer by default. If specified, the ndigits argument will round up the input to the number of decimal places entered.**

<img src= "img/round.png">

### 9) Set Function

- **Sets are one of the four built-in collection data types in Python, and is used to store multiple items in a single variable. Set items are unordered, unchangeable, and do not allow duplicate values. The `set()` function takes in another collection object such as a list or tuple, and outputs a set.**

<img src= "img/set.png">

### 10) All and any Function

- **The `all()` function takes in an iterable such as a list or tuple and returns True if all the elements in the iterable are true, and False if one or more of the items are false.**

- **The `any()` function accepts an iterable as its input and returns True if at least one element is true. It returns False if no single element in the list is true.**

<img src= "img/any&all.png">


### 11) Eval Function

- **The `eval()` function allows a user to run Python code from a string-based or compiled-code-based input. This function is especially handy when you???re trying to evaluate Python expressions that come in a string format, such as a mathematical expression.**

<img src= "img/eval.png">


### 12) Format Function

-**The `format()` function returns a formatted representation of a value based on a specified format. It takes in two arguments, the value to be formatted, and a specification of how the value is to be formatted.**

<img src= "img/format.png">


## Resources

- [Medium Article](https://medium.com/@jawadkr111/20-powerful-pandas-functions-for-your-data-analysis-da7b75600798) 


