# Linear Regression - Supervised Learning
Linear regression is a statistical method used to model the relationship between two variables by fitting a linear equation to the observed data. In other words, linear regression is a way to analyze the relationship between a dependent variable and one or more independent variables.

## Example
Let's say you're a real estate agent and you want to help a client price their home. You believe that the price of a home is related to its size (in square feet), so you decide to use linear regression to model this relationship.

You gather data on the prices and sizes of 10 homes that have recently sold in the client's neighborhood, and plot the data on a graph. The x-axis represents the size of the homes (in square feet) and the y-axis represents their prices (in dollars).

You notice that the points on the graph seem to form a roughly straight line, with larger homes generally selling for higher prices.

Using linear regression, you can find the equation for the line that best fits the data. The equation will have the form y = mx + b, where y is the price of the home, x is the size of the home, m is the slope of the line, and b is the y-intercept (the price of a home with size 0).

This is just a simple example, but the principles of linear regression apply to many different fields and types of data

## Imports
from sklearn.linear_model import LinearRegression

import pandas as pd

import numpy as np

import matplotlib.pyplot as plt
