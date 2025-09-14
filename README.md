NumPy, PyTorch, and Data Visualization Examples

This repository contains example code demonstrating the use of NumPy, PyTorch, and Seaborn/Matplotlib for generating arrays, defining functions, and visualizing data, including MNIST digits. Each script is labeled with the #SK97 tag for reference.

1. Generating Random NumPy Arrays
Description:
Generates a 4x4 array of random numbers between 0 and 1 using NumPy.
The array is different on every run unless a random seed is set.
This is useful for testing or initializing random data in machine learning tasks

2. Defining and Plotting Functions Using PyTorch
Example 1: Quadratic Function
Description:

Defines 
using PyTorch operations.
Creates 100 evenly spaced x-values using NumPy.
Evaluates the function on a PyTorch tensor and converts back to NumPy for plotting.
Uses Seaborn to display a smooth line plot.

Example 2: Cubic Function
Description:
Defines a cubic function 
Expands the x-axis range to visualize the characteristic S-shaped cubic curve.
Demonstrates flexibility in function plotting using PyTorch tensors and Seaborn.

3. Visualizing MNIST Digit Images
Description:
Retrieves a single batch from a PyTorch DataLoader (e.g., MNIST).
Visualizes digits in different arrangements: single, four in a row, and eight in a row.
Uses Matplotlib for plotting and hides axes for a cleaner visualization.
Flexible for experimenting with different numbers of images and layouts
