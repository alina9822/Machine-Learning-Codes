# Machine Learning Codes

This repository contains a collection of machine learning exercises, coursework projects, and experiment notebooks covering foundational and advanced topics in ML. The projects span data preprocessing, ensemble learning, neural networks, federated learning, dimensionality reduction, and EM-based clustering.

## Repository Overview

The codebase is organized by topic and each folder contains one or more notebooks, datasets, or supporting documents.

| Area | Folder | Description |
| --- | --- | --- |
| Data preprocessing | [Data Preprocessing and Feature Engineering](Data%20Preprocessing%20and%20Feature%20Engineering) | Cleaning, transformation, feature engineering, and exploratory analysis on tabular data. |
| Federated learning | [Federated Learning from scratch](Federated%20Learning%20from%20scratch) | A from-scratch implementation or study of federated learning using distributed training ideas and FashionMNIST data. |
| Ensemble methods | [Logistic Regression with Bagging and Stacking](Logistic%20Regression%20with%20Bagging%20and%20Stacking) | Logistic regression combined with bagging and stacking techniques, with dataset notes and experiment code. |
| Neural networks | [Neural Networkand  Backpropagation](Neural%20Networkand%20%20Backpropagation) | Neural network training logic and backpropagation experiments. |
| Dimensionality reduction | [PCA-EM](PCA-EM) | Principal Component Analysis and Expectation-Maximization-related work with sample datasets. |
| Utilities | [tools](tools) | Helper scripts for notebook normalization or project maintenance. |

## Top-Level Files

- [1905099_ML_blog.md](1905099_ML_blog.md): A write-up related to a machine learning paper as part of the tasks of the machine learning lab.
- [README.md](README.md): Repository overview and usage notes.

## Project Structure

```text
Machine-Learning-Codes/
├── 1905099_ML_blog.md
├── Data Preprocessing and Feature Engineering/
│   ├── Code.ipynb
│   └── WA_Fn-UseC_-HR-Employee-Attrition.csv
├── Federated Learning from scratch/
│   ├── data/
│   └── fed_learning_integrated.ipynb
├── Logistic Regression with Bagging and Stacking/
│   ├── Dataset.md
│   ├── Specification.pdf
│   └── offline2.ipynb
├── Neural Networkand  Backpropagation/
│   ├── Code.ipynb
│   └── Specification.pdf
├── PCA-EM/
│   ├── Code.ipynb
│   ├── Specification.pdf
│   ├── em_data.txt
│   └── pca_data.txt
├── tools/
│   └── nb_normalize.py
├── .gitignore
├── .venv/
└── README.md
```

## Learning Areas Covered

- Data cleaning and preparation
- Feature engineering and transformation
- Logistic regression and classification
- Bagging and stacking ensemble methods
- Neural networks and gradient-based optimization
- Federated learning concepts
- PCA and EM-based data modeling
- Experiment tracking through notebooks and reports

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook or JupyterLab
- Common scientific libraries such as NumPy, pandas, scikit-learn, matplotlib, and seaborn

### Environment setup

This repository includes a virtual environment in the project root:

```bash
cd Machine-Learning-Codes
source .venv/bin/activate
```

If the environment is missing or needs to be recreated, install the standard ML stack:

```bash
python -m venv .venv
source .venv/bin/activate
pip install notebook jupyter pandas numpy matplotlib seaborn scikit-learn
```

### Running the notebooks

Open Jupyter from the project root:

```bash
jupyter notebook
```

or:

```bash
jupyter lab
```

Then open any notebook under the topic folders and run the cells in order.

## Notes

- This project is mainly educational and research-oriented.
- Some folders contain assignment specifications and coursework data in addition to code.
- Results may vary depending on environment, dataset preprocessing, and package versions.

## Suggested Use

1. Start with the data-focused notebook to understand preprocessing and feature engineering.
2. Move to classification and ensemble notebooks for model-building patterns.
3. Explore neural networks and dimensionality reduction topics as you progress.
4. Use the federated learning notebook to understand distributed training concepts.

## License

This repository does not currently declare a formal license. If you plan to reuse or distribute the code, check with the repository owner before using it in a public or commercial context.

## Summary

The repository is a practical machine learning portfolio covering both theory and implementation. It is well suited for students or learners who want to study core ML methods through executable notebooks and structured experiments.
