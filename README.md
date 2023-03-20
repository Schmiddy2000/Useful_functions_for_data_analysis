# Useful functions for data analysis

In this repository I want to create useful functions that can turn your 'raw' data with relatively minor tweaks into plots and values you can use in your science projects.

## Overview of available functions:

Here is a list of all functions in this repository including a quick overview of their recommended usages, parameters and optionally some function-specific notes.

### $\chi^2$-minimization
1. Usage:
- Finds the best fit for a set of data points when given a function with the expected course.

2. Parameters
- print_output: Boolean that determines, weather the function prints all computed values. Defaults to False.
- make_plot: Boolean that determines, weather the function plots the . Defaults to False.
- model_func: Has to be a function, that takes an $x$ value as an input and returns a value for y. One other paramter is allowed.

3. Limitations
- Only works with one parameter yet.
