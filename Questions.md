---
layout: page
title: Questionverse
order: 5
permalink: /questionverse
---

* TOC
{:toc}

# Chapter 1: Warming up with Basics 
1. Use the python `print` command and figure out ways in which you can display things on the terminal. 
2. Print the following using four print statements: 
```
*
**
***
****
```
3. Figure out how to input a number and display it using print statement.
4. Understand how to use a ```if loop``` in python. Ask the user to enter a number and check if the number is even or odd.
5. Print a sequence of numbers starting from the number **a** with common difference **d**. Go on till you reach the number **b**.   
```
Enter a value for a: 10
Enter a value for d: 3
Enter a value for b: 20
Output: 10 13 16 19
```


6. Enter a number and check if it is prime or not. 
7. Input integers `i` and `j` and create a list comprising of all prime numbers between them. 

8. Observe the following code :
* What does the following code do:
```python
print("Enter a number")
k=input()
k=int(k)
for i in range(k):
		for j in range(i):
		print("*",end=' ')
print("")
```
* Something is wrong in this code. Fix it!

9. Write a script to print the following: 
```
Input a number: 5
Output: 
       *
      ***
  *****
 *******
*********
```

10. Write a script to print the following zig zag:
```
*
 *
  *
   *
        *
```

Input parameters: `number of lines`, `inclination` 
Note: Input parameters are _self-explanatory_, `inclination` is a value between *0* and *1*. Lesser the inclination, more vertical the stick. 

#### **Assignment:** Watch [this video](https://www.youtube.com/watch?v=JA_70M-ma-k) and write a piece of code to solve this problem.  

# Chapter 2 : Lists 

0. Find the least element in a given list *L*.
0. Find the greatest element in a given list *L*.
1. Create a list *L* of integers between *i* and *j*. 
2. Create a list *L* of prime numbers between *i* and *j*.
3. Create a list of lists. Eg: 
```
L=[[1,2,3],[4,5,6],[7,8,9]]
```
4. Understand how to plot using python's ```matplotlib```. Simulate the birthday paradox and plot the possibility of failure as we increase the number of students in the class.  
7. Program a rectangular spiral. You only need to output the list with the desired number of entries:
```L=['R','U','L','L','D','D','R','R','R','U','U','U']```
8. Program an outward spiral.
9. Create a list comprising of 1000 elements with entries +1 or -1. Find out the segment which adds up to maximum.  

#### **Assignment:** Implement bubble sort and binary search.

# Chapter 3 : Functions
All the questions in this chapter are required to be programmed using functions only.

1. Write a function to compute the factorial of a number. 
2. Write a function to compute the GCD of two numbers.
3. Write a function to compute the GCD of three numbers. 
4. Write a function to compute the LCM of two numbers.
5. Write a function to accept a list L and return a sorted list.
6. The following questions are to be programmed without sorting the list. 
	* Given a list *L* find the least element in it. 
	* Given a list *L* find the second, third and fourth least elements in it. 
6. Given a list *L* find the $k$th least element in it. 
7. Implement the following questions using functions:
	* Bubble Sort
	* Binary Search
8. Implement Merge Sort
9. Implement Quick Sort
	* Merge Sort
	* Quick Sort

#### **Assignment:** Solve [this](https://drive.google.com/file/d/1lSkRJ8ZTApUHpuRnITsdlI-o_4FRs-K2/view?usp=sharing) problem. 
