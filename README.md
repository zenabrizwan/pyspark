# PySpark Basics Notebook

This repository contains a Jupyter Notebook (`pysparkbasics.ipynb`) that demonstrates fundamental operations using the PySpark library.

## Overview

The `pysparkbasics.ipynb` notebook covers the following basic PySpark functionalities:

* **Initialization:** Setting up a SparkSession and SparkContext.
* **Data Loading:** Reading data from CSV files (`Movies.csv` and `wine.csv`).
* **DataFrame Operations:**
    * Displaying DataFrame content and schema.
    * Filtering rows based on conditions.
    * Selecting specific columns.
    * Displaying a limited number of rows (`show()`, `tail()`).
    * Sorting DataFrames.
* **Data Exploration:**
    * Printing the DataFrame schema (`printSchema()`).
    * Generating descriptive statistics (`describe()`).
* **Handling Missing Data:** Dropping rows with null values (`na.drop()`).
* **Introduction to MLlib (Imports Only):** Importing basic clustering algorithms (`KMeans`, `BisectingKMeans`), feature transformers (`VectorAssembler`, `StandardScaler`), and evaluation metrics (`ClusteringEvaluator`). **Note:** The notebook currently only imports these modules and doesn't implement any machine learning tasks.

## Files

* `pysparkbasics.ipynb`: The main Jupyter Notebook containing the PySpark code.
* `Movies.csv`: A sample CSV file (the structure and content are not described here, please refer to the notebook for how it's used).
* `wine.csv`: Another sample CSV file used for demonstration purposes.

**Note:** The `Movies.csv` and `wine.csv` files are assumed to be in the same directory as the notebook when it is executed.

## Getting Started

To run this notebook, you will need:

1.  **Python:** Make sure you have Python installed on your system.
2.  **Apache Spark:** You need to have Apache Spark installed and configured.
3.  **PySpark:** The PySpark library needs to be installed. You can install it using pip:
    ```bash
    pip install pyspark
    ```
4.  **Jupyter Notebook:** To open and run the `.ipynb` file, you need Jupyter Notebook or JupyterLab installed:
    ```bash
    pip install notebook  # or pip install jupyterlab
    ```
