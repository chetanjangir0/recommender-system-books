# recommender-system-books

*Company*: CODTECH IT SOLUTIONS

*Name*: Chetan

*Inern Id*: CT04WM04

*Domain*: Machine Learning

*Duration*: 4 weeks

*Mentor*: Neela Santosh

A simple book recommendation system implemented using the Singular Value Decomposition (SVD) algorithm.

## Overview

This repository contains the code for a book recommendation system. The system utilizes collaborative filtering techniques, with the SVD algorithm showing the best performance based on RMSE and MAE metrics.

## Key Components

* **`codtech task 4.ipynb`**: Contains the Python code for data loading, preprocessing, model training (SVD), and generating recommendations.
* [goodbooks 10k](https://www.kaggle.com/datasets/zygmunt/goodbooks-10k?select=ratings.csv): The datasets used for training and evaluating the recommendation system.

## Getting Started (Jupyter Notebook)

1.  **Clone the repository:**
    ```bash
    git clone [repository URL]
    cd svd-book-recommender  # Or your repository name
    ```

2.  **[Optional: Set up a virtual environment (recommended)]:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Linux/macOS
    venv\Scripts\activate  # On Windows
    ```

3.  **Install dependencies (if you haven't already):**
    ```bash
    pip install numpy pandas scikit-surprise ipykernel
    ```
    * **`numpy`**: For numerical operations.
    * **`pandas`**: For data manipulation and analysis.
    * **`scikit-surprise`**: For implementing recommendation algorithms like SVD.
    * **`ipykernel`**: To run Jupyter notebooks.

4.  **Launch Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
    This command should open Jupyter Notebook in your web browser.

5.  **Navigate to the notebook:**
    Browse the file structure in your Jupyter Notebook interface and open the `.ipynb` file containing your recommendation system code (e.g., `recommendation_notebook.ipynb`).

6.  **Run the notebook cells:**
    Execute the cells in the notebook sequentially by selecting a cell and pressing `Shift + Enter` or by clicking the "Run" button in the toolbar. The notebook should guide you through the data loading, model training, and recommendation generation process.

**Note:** Ensure that any data files (e.g., `ratings.csv`, `books.csv`) are located in the same directory as your Jupyter Notebook or that the file paths in your notebook code are correctly pointing to their location.

## Results

The Singular Value Decomposition (SVD) model achieved the following performance:

* **RMSE:** 0.8181
* **MAE:** 0.6358
