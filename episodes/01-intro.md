---
title: Python Fundamentals
teaching: 40
exercises: 20
---

::::::::::::::::::::::::::::::::::::::: objectives

- Become familiar with mathematical operators and in-built functions.
- Become more confident using Juypter notebooks (e.g., writing & submitting cells).
- Understand the order of operations.

::::::::::::::::::::::::::::::::::::::::::::::::::

:::::::::::::::::::::::::::::::::::::::: questions

- How do we process mathematical operations in Python?
- What happens if we make a mistake?


::::::::::::::::::::::::::::::::::::::::::::::::::


## Simple calculation 

Any Python interpreter can be used as a calculator:

```python
3 + 5 * 4
```

```output
23
```

### Subtraction
 
```python
10 – 5 #(subtraction) 
```


```output
5
```
### Addition
```python
10 + 5 #(addition) 
```

```output
15
```
### Multiplication

```python
10 * 5 #(multiplication) 
```

```output
50
```

### Division

```python
10 / 5 #(division) 
```

```output
2
```

### Exponentiation

```python
5 ** 2 #(exponentiation) 
```

```output
25
```

### Modulus

```python
10 % 3 #(modulus)  
```

```output
1
```

Note: anything following a '#' is considered a comment. Comments are not read by Python they are just used to inform users.


### Order of operations

Question: Before you enter the next calculation, take a second and consider what answer would you be expecting?

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



## Getting Help
Use the built-in function `help` to get help for a function.
Every built-in function has extensive [documentation that can also be found online](https://docs.python.org/3/library/index.html).

```python
help(print)
```

```output
Help on built-in function print in module builtins:

print(*args, sep=' ', end='\n', file=None, flush=False)
    Prints the values to a stream, or to sys.stdout by default.

    sep
      string inserted between values, default a space.
    end
      string appended after the last value, default a newline.
    file
      a file-like object (stream); defaults to the current sys.stdout.
    flush
      whether to forcibly flush the stream.
```

If you skip around and run cells randomly, you may not even know whether x is 10 or 25. That is where notebooks get chaotic fast.

### Problems caused by running out of order
* Name errors: variables or functions are missing
* Old values: variables keep outdated data from earlier runs
* Confusing bugs: results change for no obvious reason
* Poor reproducibility: others cannot get the same output
* Hidden dependencies: a cell works only because of some earlier unseen action


### Best practice

A good notebook should be able to run from top to bottom without errors.
That is the gold standard.

This help message (the function's "docstring") includes a usage statement, a list of parameters accepted by the function, and their default values if they have them.

It is normal to encounter error messages while programming, whether you are learning for the first time or have been programming for many years.
[We will discuss error messages in more detail later](./09-errors.md). 
For now, let's explore how people use them to get more help when they are stuck with their Python code.

* Search the internet: 
  paste the last line of your error message or the word "python" and a short description of what you want to do into your favourite search engine 
  and you will usually find several examples where other people have encountered the same problem and came looking for help.
    * [StackOverflow](https://stackoverflow.com/questions) can be particularly helpful for this: answers to questions are presented as a ranked thread ordered according to how useful other users found them to be.
    * **Take care:** copying and pasting code written by somebody else is risky unless you understand exactly what it is doing!
* Ask somebody "in the real world". 
  If you have a colleague or friend with more expertise in Python than you have, show them the problem you are having and ask them for help.

[We will discuss more debugging strategies in greater depth later in the lesson](./11-debugging.md).

:::::::::::::::::::::::::::::::::::::::: keypoints

- Built-in functions are always available to use (without additional libraries).
- Use `help(thing)` to view help for something.
- You may have seen some error messages already, they provide information about what has gone wrong with your code and where, we will look at error message in more detail later in the course.

::::::::::::::::::::::::::::::::::::::::::::::::::


