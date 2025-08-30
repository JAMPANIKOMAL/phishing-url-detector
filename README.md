# AI-Powered Phishing URL Detector

This project addresses the SIH1454 problem statement by the National Technical Research Organisation (NTRO) for the Smart India Hackathon (SIH).

## About The Project

Phishing attacks are a prevalent and dangerous cyber threat, leading to financial and data losses. This project develops a machine learning system to detect phishing websites based on URL features. By analyzing the lexical and structural characteristics of URLs, the model classifies them as "benign" or "phishing," providing an additional security layer for users.

## Tech Stack

- **Python**: Core programming language  
- **Pandas & NumPy**: Data manipulation and numerical operations  
- **Scikit-learn**: Machine learning model development and evaluation  
- **Matplotlib & Seaborn**: Data visualization  
- **Jupyter Notebook**: Interactive development and documentation  

## Project Structure

The project is organized into modular Jupyter notebooks:

- `01_data_sourcing_and_exploration.ipynb`: Downloads the raw URL dataset and performs exploratory data analysis (EDA).
- `02_feature_engineering_and_preprocessing.ipynb`: Extracts features from URLs, including length, domain, path, special characters, and suspicious keywords. Prepares and scales data for modeling.
- `03_model_development.ipynb`: Trains machine learning models such as Logistic Regression, Random Forest, and Support Vector Machines. Evaluates models using various metrics.
- `04_results_visualization.ipynb`: Visualizes model performance with a confusion matrix and feature importance plot.

## Getting Started

To set up the project locally, follow these steps:

### Prerequisites

- Install Anaconda or Miniconda to manage Python environments.

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your_username/phishing-url-detector.git
    cd phishing-url-detector
    ```
2. Create a Conda environment:
    ```bash
    conda create --name phishing-env python=3.9
    conda activate phishing-env
    ```
3. Install required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Acknowledgments

- Guidance and assistance provided by Gemini.
- Dataset sourced from the open-source community.
