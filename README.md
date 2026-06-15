# Data Cleaning and Exploratory Data Analysis (EDA)

This project focuses on cleaning, preprocessing, and exploring the **Ames Housing Dataset** to understand the relationships between house features and sale prices. It includes data inspection, statistical analysis, feature correlation analysis, visualization, and preparation of the dataset for machine learning models.

The notebook demonstrates common data science workflows using Python libraries such as **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**, **SciPy**, and **Scikit-learn**.

## Features

* Load and inspect the Ames Housing dataset
* Explore numerical and categorical variables
* Analyze the distribution of house prices
* Perform correlation analysis
* Visualize relationships between features
* Apply data normalization and scaling
* Prepare the dataset for machine learning tasks

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* Scikit-learn
* Jupyter Notebook

---

# Environment Setup

## 1. Clone the repository

```bash
git clone <repository-url>
cd <repository-name>
```

---

## 2. Create a virtual environment

### Linux (Fedora)

```bash
python3 -m venv .venv
```

Activate it:

```bash
source .venv/bin/activate
```

---

## 3. Upgrade pip

```bash
pip install --upgrade pip
```

---

## 4. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scipy scikit-learn jupyter notebook
```

Or create a `requirements.txt` file:

```txt
pandas
numpy
matplotlib
seaborn
scipy
scikit-learn
jupyter
notebook
```

Then install:

```bash
pip install -r requirements.txt
```

---

## 5. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
DataCleaning.ipynb
```

---

# Project Structure

```text
.
├── DataCleaning.ipynb
├── datacleaning.py
├── Ames_Housing_Data.tsv
└── README.md
```

---

# Running the Project

After starting Jupyter Notebook, open:

```text
DataCleaning.ipynb
```

and run the cells sequentially to reproduce the data cleaning and exploratory data analysis workflow on the Ames Housing dataset.

---

## Requirements

* Python 3.10+
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* Scikit-learn
* Jupyter Notebook
