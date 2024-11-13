# PBScreen
High-Throughput Screening of Placental Barrier–Permeable Contaminants Based on Multifusion Deep Learning

# Overview
This repository contains code and data related to molecular data analysis and machine learning modeling. The goal is to provide tools and examples for working with molecular descriptors and graph representations to predict molecular properties.

# Code Files
## Batch Train.ipynb
- This Jupyter Notebook is used for training models in a batch processing manner. 
## Benchmark.ipynb
- The `Benchmark.ipynb` notebook is designed to evaluate and compare the performance of different models or algorithms.
## Descriptors.ipynb
- Focuses on the calculation and analysis of molecular descriptors. It include functions for generating RDKit descriptors from molecular structures.
## Fingerprint.ipynb
- Deals specifically with fingerprinting techniques for molecules. Fingerprints are a way to represent the structural features of molecules in a compact form. This notebook covers methods for generating fingerprints, comparing fingerprints between molecules.
## Import.ipynb
- Presumably used for importing necessary libraries, datasets, or other external resources into the analysis environment.
## MolecularGraph.ipynb
- Concentrates on the construction and manipulation of molecular graphs. Molecular graphs are a powerful way to represent the connectivity and structure of molecules. This notebook may include functions for converting molecular structures into graph representations and extracting graph-based features for use in deep learning models.
## Multi-Fusion.ipynb
- The fusion or combination of multiple data modalities or models. It explores techniques for integrating different types of molecular information to improve the performance of predictive models.
## requirements.txt
- Lists all the Python packages and their versions required to run the code in this repository. To set up the correct environment, you can use a package manager like `pip` to install the packages specified in this file. For example, you can run `pip install -r requirements.txt` in the terminal to install all the necessary dependencies.

# Data Files
## demo.xlsx (in the Data ZIP)
- This Excel file contains a sample dataset of molecular data. The data in this file include molecular structures, PB permeability labels, and name of compounds. You can use the code in the notebooks to load and analyze this data.

# Prerequisites
- Python 3.9 installed on your system.
- Jupyter Notebook or a compatible environment to run the `.ipynb` files.
- Install all the required Python packages listed in the `requirements.txt` file using a package manager like `pip`.

# Usage
1. **Set up the environment**:
   - Install Python 3.9 if not already installed.
   - Navigate to the project directory in the terminal and run `pip install -r requirements.txt` to install the necessary packages.
2. **Explore the notebooks**:
   - Open each Jupyter Notebook (`*.ipynb` files) in a Jupyter Notebook environment.
   - Follow the code cells in each notebook to understand and execute the analysis or modeling steps. You can modify the code as needed for your specific use case.
   - For example, in `Batch Train.ipynb`, you can adjust the training parameters and run the training process. In `Benchmark.ipynb`, you can evaluate the performance of different models on your data.
3. **Use the demo data**:
   - Unzip the Data ZIP file and locate the `demo.xlsx` file.
   - In the notebooks, you can use functions to load and analyze this sample data. You can also use it as a reference to understand the expected data format and structure when working with your own molecular data.

# License
This code and data are provided under the [Apache License 2.0](LICENSE). You are free to use, modify, and distribute them for both commercial and non-commercial purposes. However, please provide appropriate attribution to the original author.

