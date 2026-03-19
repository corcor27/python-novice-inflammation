---
title: Python Fundamentals
teaching: 40
exercises: 20
---

::::::::::::::::::::::::::::::::::::::: objectives

- Become familiar with mathematical operators and in-built functions.
- Become confident using the console to run mathematical operations.
- Understand the order of operations.

::::::::::::::::::::::::::::::::::::::::::::::::::

:::::::::::::::::::::::::::::::::::::::: questions

- How do we process mathematical operations in Python

::::::::::::::::::::::::::::::::::::::::::::::::::


## Simple calculation 

Any Python interpreter can be used as a calculator:

```python
3 + 5 * 4
```

```output
23
```

```python
10 – 5 #(subtraction) 
```


```output
5
```

```python
10 + 5 #(addition) 
```

```output
15
```


```python
10 * 5 #(multiplication) 
```

```output
50
```

```python
10 / 5 #(division) 
```


```output
2
```




```python
5 ** 2 #(exponentiation) 
```

```output
25
```

```python
10 % 3 #(modulus)  
```

```output
1
```

Note: anything following a '#' is considered a comment. Comments are not read by Python they are just used to inform users.


### Order of operations

> ## Question: Before you enter the next calculation, take a second and consider what answer would you be expecting?
```python
6 + 9 / 3 
```

```output
9
```



If the answer was **not** what you were expecting you will need to become clear on order of operations in Python. 

 
### Remember **PE(DM)(AS)** 

* **P**arentheses 

* **E**xponentiation 

* **D**ivision/**M**ultiplication\*  

* **A**ddition/**S**ubtraction\*  

 Operators with same precedent are calculated left to right. 

 
This tells you what order mathematical operations will be performed and ensures consistency during evaluation.  

To make this concept clearer, try: 

```python
(6 + 9) / 3 
```


```output
5
```


Using brackets we have manipulated the order of operations to perform the addition before the division. Be conscious of how you structure your mathematical operations to ensure the desired results but also readability of your code. 




:::::::::::::::::::::::::::::::::::::::: keypoints

- Import a library into a program using `import libraryname`.
- Use the `numpy` library to work with arrays in Python.
- The expression `array.shape` gives the shape of an array.
- Use `array[x, y]` to select a single element from a 2D array.
- Array indices start at 0, not 1.
- Use `low:high` to specify a `slice` that includes the indices from `low` to `high-1`.
- Use `# some kind of explanation` to add comments to programs.
- Use `numpy.mean(array)`, `numpy.amax(array)`, and `numpy.amin(array)` to calculate simple statistics.
- Use `numpy.mean(array, axis=0)` or `numpy.mean(array, axis=1)` to calculate statistics across the specified axis.

::::::::::::::::::::::::::::::::::::::::::::::::::


