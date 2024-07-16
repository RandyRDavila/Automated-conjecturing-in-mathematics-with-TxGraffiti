# TxGraffiti Notebooks

## Overview

This directory contains a collection of Jupyter notebooks that demonstrate the capabilities of the TxGraffiti algorithm in generating mathematical conjectures across various domains. Each notebook is self-contained, meaning it includes all necessary code and data to run independently without requiring additional files. This setup allows users to seamlessly run the notebooks on Google Colab or their local environments and validate the TxGraffiti algorithm presented in the paper for which this repository was made from.

## Notebooks

1. **[Integers](integers.ipynb)**
   - **Description**: Applies the TxGraffiti algorithm to generate conjectures on positive integers. Explores relationships between various numerical properties of integers.
   - **Colab**: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/RandyRDavila/AI-discovery-in-mathematics-with-TxGraffiti/blob/main/notebooks/integers.ipynb)

2. **[Matrices](matrices.ipynb)**
   - **Description**: Uses TxGraffiti to generate conjectures on square symmetric matrices. Investigates relationships between different matrix properties.
   - **Colab**: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/RandyRDavila/AI-discovery-in-mathematics-with-TxGraffiti/blob/main/notebooks/matrices.ipynb)

3. **[Scale-Free Graphs](scale_free_graphs.ipynb)**
   - **Description**: Applies TxGraffiti to generate conjectures on scale-free graphs. Studies various graph-theoretic properties.
   - **Colab**: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/RandyRDavila/AI-discovery-in-mathematics-with-TxGraffiti/blob/main/notebooks/scale_free_graphs.ipynb)

4. **[Breast Cancer](breast_cancer.ipynb)**
   - **Description**: Utilizes TxGraffiti to generate conjectures on the well-known breast cancer dataset. Explores relationships between different features and the target variable.
   - **Colab**: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/RandyRDavila/AI-discovery-in-mathematics-with-TxGraffiti/blob/main/notebooks/breast_cancer.ipynb)

5. **[Sequences](sequences.ipynb)**
   - **Description**: Applies TxGraffiti to generate conjectures on various numerical sequences. Investigates relationships between different sequence properties.
   - **Colab**: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/RandyRDavila/AI-discovery-in-mathematics-with-TxGraffiti/blob/main/notebooks/sequences.ipynb)

6. **[Wine Data](wine_data.ipynb)**
   - **Description**: Uses TxGraffiti to generate conjectures on the wine quality dataset. Studies the relationships between different chemical properties and wine quality.
   - **Colab**: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/RandyRDavila/AI-discovery-in-mathematics-with-TxGraffiti/blob/main/notebooks/wine_data.ipynb)

## Instructions

1. **Opening Notebooks in Colab**:
   - Click the Colab badge next to the notebook description to open it directly in Google Colab. This allows you to run the notebook in an interactive environment without any setup.

2. **Running Notebooks Locally**:
   - Clone the repository to your local machine.
   - Ensure you have Jupyter installed. You can install it using `pip install jupyter`.
   - Navigate to the `notebooks` directory and start Jupyter:
     ```sh
     jupyter notebook
     ```
   - Open the desired notebook from the Jupyter interface and run all cells to execute the code.

3. **Dependencies**:
   - Each notebook includes the necessary code to generate the dataset and apply the TxGraffiti algorithm. The required packages are typically imported at the beginning of each notebook. Ensure you have the required packages installed, such as `numpy`, `pandas`, `scikit-learn`, and `pulp`.

4. **Self-Contained Notebooks**:
   - Each notebook is designed to be self-contained. This means all the data generation and processing steps are included within the notebook itself, allowing for easy execution and reproducibility without the need for additional files.

Happy conjecturing!
