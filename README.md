# Exploring Clustering and Dimensionality Reduction through Maternal Mortality Analysis in Southeast Asia

This project explores maternal mortality reporting patterns in Southeast Asia using various machine learning techniques. We analyze the gap between observed maternal deaths and estimated mortality rates to identify underlying patterns in vital registration systems.

The analysis tests three key hypotheses regarding clustering stability and dimensionality reduction to better understand data quality issues in the region.

## Repository Structure

* **`BG4104_Assignment_2_Code.ipynb`**: The main Jupyter Notebook containing the Python code for data loading, preprocessing, clustering (K-Means, GMM), dimensionality reduction (PCA, ICA), and visualization.
* **`main_data.csv`**: The dataset used for the analysis.
* **`requirements.txt`**: A list of Python dependencies required to run the project.

## Getting Started

Follow these instructions to set up the environment and run the analysis.

### Prerequisites

Ensure you have Python installed (preferably Python 3.8 or higher).

### Installation

1.  **Clone the repository** (or download the files to a local folder):
    ```bash
    git clone https://github.com/sannankanwar/BG4104Assignment2.git
    cd (your folder here)
    ```

2.  **Install Dependencies**:
    It is recommended to run this in a virtual environment. You can install all necessary libraries using the `requirements.txt` file:
    ```bash
    pip install -r requirements.txt
    ```

## How to Run the Code

1.  **Launch Jupyter Notebook**:
    In your terminal, navigate to the project directory and run:
    ```bash
    jupyter notebook
    ```

2.  **Open the Notebook**:
    Click on `BG4104_Assignment_2_Code.ipynb` in the Jupyter interface to open it.

3.  **Run the Analysis**:
    * Ensure `main_data.csv` is in the same directory as the notebook.
    * Run all cells (Cell -> Run All) to generate the figures and analysis outputs.

## Project Overview

We utilized the following methods to analyze the dataset:

* **Clustering**: Compared K-Means (hard clustering) vs. Gaussian Mixture Models (GMM) to identify distinct development stages and system transition patterns.
* **Dimensionality Reduction**: Compared PCA (variance maximization) vs. ICA (independent source separation) vs Random Projections to extract insights from high-dimensional health data.

## Authors

* @Sannan
* @Taha
* @Japheth
