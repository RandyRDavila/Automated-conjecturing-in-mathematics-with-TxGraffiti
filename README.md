# Automated-conjecturing-in-mathematics-with-TxGraffiti

This repository contains the code, data, and results for the paper "Automated conjecturing in Mathematics with TxGraffiti".

## Overview

TxGraffiti is an AI conjecturing program that generates mathematical conjectures using a combination of machine learning techniques and heuristics. This repository provides the implementation of TxGraffiti, along with datasets and Jupyter notebooks demonstrating its application across various mathematical domains.

## Repository Structure

- `notebooks/`: Contains Jupyter notebooks for running the TxGraffiti algorithm on different types of data.
  - [`TxGraffiti_Experiment.ipynb`](https://colab.research.google.com/github/RandyRDavila/AI-discovery-in-mathematics-with-TxGraffiti/blob/main/notebooks/TxGraffiti_Experiment.ipynb) : The notebook associated with Section 4 in the corresponding manuscript.
  - [`MoreComplexLinearInequalities.ipynb`](https://colab.research.google.com/github/RandyRDavila/AI-discovery-in-mathematics-with-TxGraffiti/blob/main/notebooks/MoreComplexLinearInequalities.ipynb) : The notebook associated with Section 4.2 in the corresponding manuscript; generating more complex inequalities.
  - [`integers.ipynb`](https://colab.research.google.com/github/RandyRDavila/AI-discovery-in-mathematics-with-TxGraffiti/blob/main/notebooks/integers.ipynb): Demonstrates conjectures on integer data.
  - [`matrices.ipynb`](https://colab.research.google.com/github/RandyRDavila/AI-discovery-in-mathematics-with-TxGraffiti/blob/main/notebooks/matrices.ipynb): Demonstrates conjectures on symmetric matrices.
  - [`scale_free_graphs.ipynb`](https://colab.research.google.com/github/RandyRDavila/AI-discovery-in-mathematics-with-TxGraffiti/blob/main/notebooks/scale_free_graphs.ipynb): Demonstrates conjectures on scale-free graphs.
  - [`breast_cancer.ipynb`](https://colab.research.google.com/github/RandyRDavila/AI-discovery-in-mathematics-with-TxGraffiti/blob/main/notebooks/breast_cancer.ipynb): Demonstrates conjectures on the breast cancer dataset.
  - [`wine_data.ipynb`](https://colab.research.google.com/github/RandyRDavila/AI-discovery-in-mathematics-with-TxGraffiti/blob/main/notebooks/wine_data.ipynb): Demonstrates conjectures on wine quality data.
  - [`karate_club_graph.ipynb`](https://colab.research.google.com/github/RandyRDavila/AI-discovery-in-mathematics-with-TxGraffiti/blob/main/notebooks/karate_club_graph.ipynb): Demonstrates TxGraffiti conjecturing on a single mathematical object.
- `LICENSE`: License for the code.
- `README.md`: This file.
- `requirements.txt`: List of dependencies.

## Installation

To install the required dependencies, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/RandyRDavila/Automated-conjecturing-in-mathematics-with-TxGraffiti.git
   cd Automated-conjecturing-in-mathematics-with-TxGraffiti
   ```

2. **Create and Activate Virtual Environment:**
    * Windows
    ```bash
    python -m venv env
    .\env\Scripts\activate
    ```
    * MacOS/Linux:
    ```bash
    python3 -m venv env
    source env/bin/activate
    ```

3. **Install Dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
Now you should have all the necessary packages installed to run the project.

## Usage

To run TxGraffiti on a dataset, open the corresponding Jupyter notebook in the notebooks/ directory and follow the instructions.


## License

This project is licensed under the MIT License - see the LICENSE file for details.