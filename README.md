# Text Classification TOPSIS Analysis

[![Python Version](https://img.shields.io/badge/python-3.8%2B-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub issues](https://img.shields.io/github/issues/your_username/text-classification-topsis)](https://github.com/your_username/text-classification-topsis/issues)
[![GitHub stars](https://img.shields.io/github/stars/your_username/text-classification-topsis)](https://github.com/your_username/text-classification-topsis/stargazers)

Welcome to the **Text Classification TOPSIS Analysis** project! This repository demonstrates how to evaluate and rank pre-trained text classification models using the TOPSIS (Technique for Order of Preference by Similarity to Ideal Solution) method. The project provides interactive visualizations and a complete pipeline—from data normalization to ranking—and saves the resulting graphs for easy sharing.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Visualizations](#visualizations)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## Overview

In this project, we compare multiple pre-trained models for text classification (e.g., BERT, RoBERTa, XLNet, DistilBERT, and ALBERT) across several evaluation criteria such as:

- **Accuracy (%)** (benefit criterion)
- **F1 Score (%)** (benefit criterion)
- **Inference Time (sec)** (cost criterion)
- **Model Size (MB)** (cost criterion)

Using the TOPSIS method, we normalize the decision matrix, apply weights to the criteria, and determine the relative closeness of each model to the ideal solution. This process results in an intuitive ranking of models based on their performance.

---

## Features

- **Interactive Visualizations:**  
  - **Bar Chart:** Displaying TOPSIS scores for ranking models.  
  - **Radar Charts:** Visualizing each model's performance across all criteria.  
  - **Heatmap:** Showing the weighted normalized decision matrix.  
  - **Pairwise Scatter Plot Matrix:** Exploring relationships between evaluation metrics.

- **Automated Graph Saving:**  
  All visualizations are automatically saved in the `results/` directory for easy review and sharing.

- **Reproducible Analysis:**  
  Easily re-run the analysis with updated metrics or weights to explore different scenarios.

---

## Project Structure

