# Cheat Sheet - Python Data Analysis

This is a summary of useful functions when working with larger amounts of data. 
The exact layout structure is still to be determined. 

## Basic concepts

This chapter will be a recap of the basics when working with arrays. We will look 
at ways to identify and retrieve specific elements from different types of data sets. 
We'll also quickly show how we can switch between different data types and structures.

### Slicing

A way commonly used to retrieve values or smaller sets of data from a larger set is 
known as slicing. This requires the object to be _iterable_. 

**Definition:** 
An object is _iterable_ if it can be looped over, meaning it needs to have a specific
order. This applies to objects such as lists, strings and tuples. 

We can define a list as follows:

<pre>
my_list = [1, 2, 3, 4, 5]
</pre>

We can access a single element of the _iterable_ by specifying its _index_ in squared
brackets behind the objects name:

<pre>
my_value = my_list[3]
</pre>

This sets `my_value` to `4` since _indices_ start at `0`. If we want to retrieve more
than one value from our data set, we need use _slicing_.

The slicing syntax is composed of up to three _parameters_. Namely, _start_index_, 
_stop_index_ and _step_size_. We can apply them onto the data set by using them like

<pre>
[start_index : stop_index : step_size]
</pre>

where the _indices_ have to be _integers_. When not specified, they default to 

    - start_index = 0
    - stop_index = len(data_set) - 1
    - step_size = 1
