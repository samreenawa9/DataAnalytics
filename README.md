# DataAnalytics
📊 Data Analytics Journey with Python  | NumPy, Matplotlib, Seaborn
This repository documents my learning journey and hands-on practice in data analytics using Python. It includes practical examples and mini-projects using core Python libraries such as NumPy, Matplotlib, and Seaborn—essential tools for any aspiring data analyst or data scientist. 
🧰 Libraries Covered
NumPy: Numerical computing with arrays, mathematical operations, statistics, and linear algebra.

Matplotlib: Data visualization through plots, bar charts, line graphs, and histograms.

Seaborn: Advanced data visualization built on top of Matplotlib with built-in themes and better styling.

Pandas : Used for working with datasets and performing EDA (exploratory data analysis).


📌 1. NumPy Basics – Array Manipulation & Statistics
import numpy as np

# Create arrays
a = np.array([1, 2, 3, 4])
b = np.arange(0, 10, 2)

# Basic operations
sum_a = np.sum(a)
mean_b = np.mean(b)
matrix = np.array([[1, 2], [3, 4]])
transpose = matrix.T

print("Sum:", sum_a)
print("Mean:", mean_b)
print("Transpose:\n", transpose)


📌 2. Matplotlib – Visualizing Trends
import matplotlib.pyplot as plt

x = [1, 2, 3, 4, 5]
y = [10, 14, 12, 18, 20]

plt.figure(figsize=(8, 5))
plt.plot(x, y, color='green', marker='o', linestyle='--')
plt.title("Line Chart Example")
plt.xlabel("Time")
plt.ylabel("Values")
plt.grid(True)
plt.show()


📌 3. Seaborn – Visualizing Datasets with Style
import seaborn as sns
import matplotlib.pyplot as plt
import pandas as pd

# Sample dataset
df = sns.load_dataset("tips")

# Histogram of total bill
sns.histplot(data=df, x="total_bill", kde=True, color="skyblue")
plt.title("Total Bill Distribution")
plt.show()

# Boxplot of total bill by day
sns.boxplot(data=df, x="day", y="total_bill", palette="pastel")
plt.title("Boxplot of Total Bills by Day")
plt.show()


🎯 Objective
This repository reflects my commitment to mastering the foundational tools of data analytics and visualization. It serves as a base for further exploration into real-world data projects, EDA, and machine learning.

