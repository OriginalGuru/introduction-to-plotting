# introduction-to-plotting

## Learning Objectives

This repository contains three Jupyter notebooks designed to improve your understanding of creating and customizing visualizations using Matplotlib and related tools.

### 1. Plotting with Matplotlib
In this notebook, you will learn how to:
- Build a **reusable plotting function** for creating custom line plots.
- Customize line styles, labels, axis limits, and subplots for multiple datasets.

### 2. Contour Plots with Matplotlib
In this notebook, you will learn how to:
- Create **contour plots** to visualize 3D data in 2D space.
- Use **filled contours** with `plt.contourf()` and **labeled contours** with `plt.contour()` and `plt.clabel()`.
- Customize plot properties, such as colormaps, axis labels, gridlines, and color bars.
- Build **reusable plotting functions** to streamline your workflow.

### 3. Interactive Plots with Ipywidgets
In this notebook, you will learn how to:
- Use **`ipywidgets`** to create **dynamic visualizations** that allow user interaction.
- Dynamically customize filled contour plots based on user input.
- Visualize and manipulate a mathematical function:
  
  $f(q_1, q_2) = k_1 \cdot q_1^2 + k_2 \cdot q_2^2 + c \cdot q_1 \cdot q_2$
  
- Adjust plot parameters like contour range and number of contours in real-time.


---

## Assignment
In this assignment, you will create your own Jupyter Notebook with a multipanel figure and sliders to explore the response of:

1. coupled oscillators;
2. an anharmonic oscillator with and without an external field.

### Background:
In class, we showed the model for an oscillator, or coupled oscillators, and the coupling to external fields can be found by knowning the symmetry of the physical system. In this exercise, we are going to use those results to anticipate what types of motion, or dynamical regimes, are possible. 

Recall that the symmetry properties we derived for 'vector-like' 1D objects were:

| symbol | 1D object    | identity | mirror_z | mirror_y | rotation_x_180 |
|--------|--------------|----------|----------|----------|----------------|
|   Q_1  | scalar       |    1     |    1     |    1     |       1        |
|   Q_2  | pseudoscalar |    1     |   -1     |   -1     |       1        |
|   Q_3  | polar vector |    1     |   -1     |    1     |      -1        |
|   Q_4  | axial vector |    1     |    1     |   -1     |      -1        |


