
# Customer Purchase Data Preprocessing

This repository contains my implementation of data preprocessing steps applied to a dummy customer purchase dataset. The goal is to gain practical experience and reinforce my theoretical knowledge by working on real data preprocessing tasks.

---

## Table of Contents
- [Overview](#overview)
- [Dataset Description](#dataset-description)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Code Structure](#code-structure)
- [Author](#author)
- [Acknowledgements](#acknowledgements)

---

## Overview

This project demonstrates basic data preprocessing techniques using a synthetic dataset representing customer purchase information. The dataset includes features such as customer demographics, purchase history, and categorical variables. The preprocessing steps include handling missing data, encoding categorical variables, splitting data, and feature scaling.

*Note:* This project is part of my efforts to translate theoretical knowledge of data preprocessing into practical implementation.

---

## Dataset Description

The dummy dataset simulates customer purchase records with the following features:

- `Country`: country name (categorical)
- `Age`: Customer's age (int)
- `salary`: Customer's salary (int) 
- `Purchased`: Whether the customer made a purchase (Yes/No)



---

## Features

- Import the dataset
- Handle missing values
- Encode categorical variables (`Country`, `Purchased`)
- finding relation between each independednt feature and target feature
- Visualize data distributions to extract meaningful insights from raw data

---

## Prerequisites

Ensure you have the following installed:

- Python 3.x
- Required libraries:
  - numpy
  - pandas
  - matplotlib
  - scikit-learn

Install the dependencies via pip:

```bash
pip install numpy pandas matplotlib scikit-learn
```

---

## Getting Started

1. Clone this repository:

```bash
git clone https://github.com/yourusername/customer-purchase-preprocessing.git
cd customer-purchase-preprocessing
```

2. Prepare your dataset in CSV format (if not already included). For this demo, the dataset is downloaded from kaggle.

3. Run the preprocessing script:

```bash
python preprocess.py
```

---

## Usage

The script will:
- importing necessary libraries
- Load the dataset
- Handle missing data (if any)
- Encode categorical variables
    - LabelEncodng
    - one hot encoding
- translating raw data into insightful data

This hands-on implementation helps bridge the gap between theoretical concepts and practical skills in data preprocessing.

---

## Code Structure

- `preprocess.py`: Main script with all preprocessing steps
- `dataset/`: dummy dataset
- `requirements.txt`: List of dependencies

---

## Author

NEERAGANTI CHANDANA - [chandananeeraganti123@gmail.com](mailto:chandananeeraganti123@gmail.com)

---

## Acknowledgements

- Inspired by tutorials on data preprocessing and machine learning.
- Libraries used: NumPy, Pandas, Matplotlib, scikit-learn.
