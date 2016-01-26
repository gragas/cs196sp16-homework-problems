# Potential Homework Problems
### CS 196 Spring 2016
These are problems that might be assigned as homework in UIUC's spring 2016 CS 196 class.

## Variables

* Create a variable `a` and assign the value `5` to it. Then, create another variable `b`, which is equal to two less than `a`.
  * What is the type of `a`?
  * What is the type of `b`?
* Suppose you are running the Python interpreter and there is a variable `a`, but you don't know the value of `a`.
  * In the Python interpreter, how can you determine the value of `a`?
  * In the Python interpreter, how can you determine the type of `a`?
  * If you aren't in the Python interpreter, how can you determine the type of `a`?
* Suppose `a = 1` and `b = 1.2`. What is the value of `a + b`? Create a new variable `c` and assign that value to it.
  * What is the type of `a`?
  * What is the type of `b`?
  * What is the type of `c`?
  * What do you get when you add an `int` to a `float`?
* Suppose you have a variable `s`. Assign `"Hello, World!"` to `s`.
  * What is the length of `s`?
  * How can you determine the length of an arbitrary `str`?
  * How do humans refer to variables of type `str`?
  * What does the expression `s * 2` evaluate to?

## Functions

* What does the following function `mysteryfunction` do?

```
def mysteryfunction(n):
    return n + 2
```

* Define a function `square` that takes a number and returns the square of it.

* Define a function `triple` that takes a string and **prints** three copies of it in a row.

* Define a function `f` that takes a number returns that that number plus five.
  * Now define a function `g` that takes a function `func` and a number `n` and returns the value of the `func` applied to `n` minus seven.
  * What is the value of `g(f, 5)`, where `g` and `f` refer to the functions you just defined?

* Do functions have to return something?

* Define a function that does nothing.

* Define a function that takes a string and returns twice the length of it.

The built-in function `map` takes as arguments a function and an `iterable` object, and returns the `iterable` object where each element is replaced with the function applied to that element. For example,

```
def double(n):
    return 2 * n
my_list = [1, 2, 3, 4]
my_doubled_list = map(double, my_list)
```

In this case, the value assigned to `my_doubled_list` is `[2, 4, 6, 8]`.

* Write a function `even` that takes a number and returns `True` if it is even, and `False` otherwise.
* Consider the list `l = [1, 2, 3, 4]`. What is the value of `map(even, l)`?