# Data Science and Machine Learning Applied to Financial Markets

A collection of Python notebooks exploring data science, financial data analysis, machine learning, and deep learning. This repository brings together practical exercises and experiments developed as part of my training in Data Science and Machine Learning Applied to Financial Markets at ITAM.

**Technologies:** Python · Jupyter Notebook · pandas · NumPy · Data Science · Machine Learning · Deep Learning

[View Repository](https://github.com/jman0306/Data-Science-and-Machine-Learning-applied-to-Financial-Markets)

---

## Table of Contents

- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Technology Stack](#technology-stack)
- [Repository Contents](#repository-contents)
- [Learning Areas](#learning-areas)
- [Datasets](#datasets)
- [Getting Started](#getting-started)
- [Running the Notebooks](#running-the-notebooks)
- [Reproducibility](#reproducibility)
- [Future Improvements](#future-improvements)
- [Disclaimer](#disclaimer)

## Project Overview

This repository contains a collection of Jupyter notebooks covering Python programming for finance, data science, machine learning, and deep learning.

The project focuses on applying computational and analytical techniques to structured datasets and exploring how statistical methods and machine learning workflows can support data-driven analysis.

Rather than representing a single end-to-end application, the repository serves as a learning portfolio documenting different analytical approaches, programming exercises, and model development concepts.

## Objectives

- Strengthen Python programming skills for financial and analytical applications.
- Explore data manipulation and exploratory data analysis.
- Apply statistical and computational techniques to structured datasets.
- Study machine learning workflows and predictive modeling concepts.
- Explore deep learning methodologies through practical notebooks.
- Develop a foundation for applying data science techniques to financial markets and other business problems.

## Technology Stack

| Technology | Purpose |
|---|---|
| Python | Core programming language for analysis and modeling |
| Jupyter Notebook | Interactive development, experimentation, and documentation |
| pandas | Data manipulation and analysis |
| NumPy | Numerical computing and array operations |
| Data visualization libraries | Exploring distributions, relationships, and analytical results |
| Machine learning libraries | Implementing and evaluating models where included |
| Deep learning frameworks | Exploring neural network approaches where included |

The exact libraries required depend on the notebook being executed.

## Repository Contents

The repository is organized into four main notebooks and supporting datasets.

| Notebook | Description |
|---|---|
| [Introduction to Python for Finance](https://github.com/jman0306/Data-Science-and-Machine-Learning-applied-to-Financial-Markets/blob/main/Introduction%20to%20Python%20for%20Finance.ipynb) | Python programming exercises and computational techniques applied to financial contexts |
| [Data Science](https://github.com/jman0306/Data-Science-and-Machine-Learning-applied-to-Financial-Markets/blob/main/Data_Science.ipynb) | Data science exercises, data exploration, and analytical workflows |
| [Machine Learning](https://github.com/jman0306/Data-Science-and-Machine-Learning-applied-to-Financial-Markets/blob/main/Machine_Learning.ipynb) | Practical exploration of machine learning concepts and modeling techniques |
| [Deep Learning](https://github.com/jman0306/Data-Science-and-Machine-Learning-applied-to-Financial-Markets/blob/main/Deep_Learning.ipynb) | Exercises exploring deep learning concepts and neural network approaches |

Additional repository resources include:

- `data/`: Supporting datasets and data files.
- `bank.csv`: A dataset used for analytical exercises.
- `SuperMarket Analysis.csv`: A dataset for data analysis exercises.

## Learning Areas

### 1. Python for Finance

Explores Python as a tool for quantitative and financial analysis, including programming fundamentals and numerical data manipulation.

Potential applications include financial data processing, quantitative calculations, and preparing datasets for further analysis.

### 2. Data Science

Focuses on the analytical workflow involved in working with structured data.

Key areas include:

- Data loading and preparation.
- Data manipulation and transformation.
- Exploratory data analysis.
- Statistical analysis and interpretation.
- Data visualization.
- Identifying patterns and relationships in datasets.

### 3. Machine Learning

Explores the concepts and workflows involved in developing machine learning models.

Relevant learning areas include:

- Preparing datasets for modeling.
- Selecting features and target variables.
- Training predictive models.
- Understanding model evaluation.
- Interpreting model outputs and limitations.

The specific algorithms and evaluation techniques should be reviewed in the corresponding notebook.

### 4. Deep Learning

Introduces computational approaches based on neural networks and deep learning architectures.

The notebook provides a practical environment for exploring model construction, training workflows, and related concepts, depending on the implementations included.

## Datasets

The repository includes supporting data files used for analytical and modeling exercises.

| Dataset | Role |
|---|---|
| `bank.csv` | Input data for dataset exploration or modeling exercises |
| `SuperMarket Analysis.csv` | Input data for analysis exercises |
| `data/` | Additional supporting data files |

The intended use, column definitions, and source of each dataset should be verified in the corresponding notebook before interpreting analytical results.

These datasets support experimentation and learning; their presence does not imply that all notebooks use financial-market price data.

## Getting Started

### Prerequisites

Before running the notebooks, make sure you have:

- Python installed.
- Jupyter Notebook or JupyterLab.
- The Python libraries required by the notebook you want to run.
- Access to the repository's datasets.

### 1. Clone the Repository

```bash
git clone https://github.com/jman0306/Data-Science-and-Machine-Learning-applied-to-Financial-Markets.git
cd Data-Science-and-Machine-Learning-applied-to-Financial-Markets
```

### 2. Create a Virtual Environment

On Windows:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

On macOS or Linux:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install Jupyter

```bash
python -m pip install jupyter ipykernel
```

Install the additional Python packages required by the notebook you intend to execute. Review its import statements to identify the necessary libraries.

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open one of the notebooks listed in the repository contents and execute its cells in sequence.

## Running the Notebooks

For the best experience:

1. Start with `Introduction to Python for Finance.ipynb` to explore the programming foundations.
2. Continue with `Data_Science.ipynb` to explore data analysis workflows.
3. Open `Machine_Learning.ipynb` to review the machine learning exercises.
4. Explore `Deep_Learning.ipynb` for the deep learning material.

This is a suggested learning sequence based on the notebook titles, not a guarantee that every notebook depends on the previous one.

Some notebooks may require specific datasets, library versions, or external resources. Verify these requirements before execution.

## Reproducibility

To make the exercises easier to reproduce across different environments, consider the following practices:

- Document the Python version used for development.
- Create a `requirements.txt` file containing the actual dependencies used by the notebooks.
- Keep the original datasets in their expected locations or document how to obtain them.
- Record the source of external datasets and any preprocessing steps.
- Document random seeds when model training involves randomness.
- Save model evaluation results and visualizations alongside the relevant analysis.
- Avoid including unnecessary generated files or large outputs in notebook commits.

## Future Improvements

Potential enhancements include:

- Add a dedicated README section for each notebook describing its objectives and key findings.
- Document the datasets, their sources, and their columns.
- Add a reproducible environment using `requirements.txt`.
- Include visualizations and selected results from the notebooks.
- Document model evaluation metrics and compare alternative approaches where appropriate.
- Add a clear distinction between educational experiments and validated predictive models.
- Organize notebooks into folders by topic as the project grows.

## Disclaimer

This repository is intended for educational purposes and portfolio demonstration. The notebooks explore data science and machine learning concepts and should not be interpreted as validated investment strategies or financial advice.

Any model outputs or analytical results should be evaluated in the context of their datasets, assumptions, methodology, and limitations before being used for real-world financial decisions.
