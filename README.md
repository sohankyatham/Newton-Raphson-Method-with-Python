# Newton-Raphson-Method-with-Python

## Description
The Newton-Raphson Method (or Newton's Method) is an iterative numerical technique used to find the roots of a function. It starts with an initial guess and iteratively refines this guess until it approaches the roots of a function. The method is based on linear approximation and requires the calculation of both the function and its derivative. This project implements the Newton-Raphson Method in Python, providing a simple and efficient way to approximate square roots.

## Project Overview
This project aims to implement the Newton-Raphson Method in Python to approximate square roots. It provides a user-friendly interface where a user can input a number and calculate its square root using the Newton-Raphson Method. The application includes features such as graphing the root approximations over iterations and saving the graph as an image file.
### Technologies Used:
\**Python:** The core programming language used for implementing the Newton-Raphson Method. 
\**Tkinter Library:** Python's standard GUI (Graphical User Interface) toolkit which was used to create the user interface for the application
\**Matplotlib Library:** A comprehensive library for creating static, animated, and interactive visualizations in Python. This library was used for plotting the graph of the root approximations over iterations.

```
# Imports
import tkinter as tk
from tkinter import filedialog
import matplotlib.pyplot as plt
from matplotlib.backends.backend_tkagg import FigureCanvasTkAgg
import webbrowser
```
