# CodeAlpha Internship - Task 03: Data Visualization

## Project Overview

This repository contains the solution for **Task 03** of my internship with **CodeAlpha**. The project focuses on using data visualization techniques to transform the `tips` dataset into meaningful charts and graphs. The goal is to craft a compelling data story by revealing key insights and patterns that can support business decision-making.

## Project Files

* **`task03.ipynb`**: The main Jupyter Notebook containing the complete code for data visualization.
* **`Results/`**: This directory contains the images of the visualizations created in the notebook.
* **`README.md`**: This file, providing an overview of the project.

## Key Visualizations & Data Stories

The visualizations in this project were designed to tell a clear story about tipping habits and support operational decisions in a restaurant.

### 1. Relationship Between Total Bill and Tip Amount

* **Visualization:** Scatter Plot
* **Story:** This chart clearly shows a strong positive correlation between the total bill and the tip amount. It also uses color to differentiate by gender (`sex`) and style to differentiate by smoking status (`smoker`), demonstrating how these factors relate to the bill and tip.
* **Key Insight:** Customers who spend more tend to leave larger tips, and this behavior is consistent across different groups.

### 2. Tips by Day of the Week

* **Visualization:** Box Plot
* **Story:** This plot compares the distribution of tips on different days of the week. The boxes show the range of tips, while the line in the middle indicates the median.
* **Key Insight:** Weekend days (Saturday and Sunday) tend to have a higher median tip amount and a wider range of tipping behavior compared to weekdays.

### 3. Average Tip Percentage by Time of Day

* **Visualization:** Bar Plot
* **Story:** This visualization provides a direct comparison of a key metric: the average tip percentage for lunch versus dinner.
* **Key Insight:** The data suggests that, on average, customers leave a higher tip percentage during dinner service than at lunch, which can inform staffing and resource allocation.

## Technologies Used

* **Python**: The core programming language.
* **Pandas**: For data handling and manipulation.
* **Matplotlib & Seaborn**: For creating all charts, graphs, and visualizations.
* **Jupyter Notebook**: The development environment for the interactive analysis.

## How to Run the Project

1.  Clone this repository to your local machine:
    ```bash
    git clone [Your-Repo-URL]
    ```
2.  Navigate to the project directory:
    ```bash
    cd [Your-Repo-Name]
    ```
3.  Install the required libraries:
    ```bash
    pip install pandas matplotlib seaborn jupyter
    ```
4.  Launch Jupyter Notebook or JupyterLab:
    ```bash
    jupyter notebook
    ```
5.  Open the `task03.ipynb` file in your browser and run the cells to see the complete analysis.

---
