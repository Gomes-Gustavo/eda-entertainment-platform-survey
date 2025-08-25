# Unwind Platform Data Analysis

This repository contains a comprehensive **data analysis** of a survey conducted for the Unwind platform, a digital entertainment platform in development designed for organizing, rating, and sharing entertainment content such as movies, series, and games. The analysis follows best practices in exploratory data analysis (EDA) and provides insights to guide platform development decisions.

## Table of Contents

- [Project Overview](#project-overview)
- [About Unwind](#about-unwind)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Jupyter Notebooks](#jupyter-notebooks)
- [Installation](#installation)
- [Author](#author)

## Project Overview

This project was developed as part of an academic requirement for the Statistics course ("Pesquisa de mercado de um produto/serviço") at Mauá Institute of Technology (Instituto Mauá de Tecnologia). It analyzes survey data collected from potential users of the Unwind platform to understand demographics, entertainment consumption patterns, and platform feature preferences.

`Note: All visualizations and analyses are presented in Portuguese to meet academic requirements.`

Key objectives include:

- Understand demographic characteristics of potential users
- Analyze entertainment consumption patterns
- Identify preferred platform features
- Evaluate platform adoption intention across different segments
- Provide data-driven recommendations for platform development

## About Unwind

Unwind is a digital entertainment platform in development by a member of the statistics project group that allows users to:
- Organize and track consumption of movies, series, and games in one place
- Create personalized shelves with ratings and bookmarks
- Build thematic collections (e.g., Marvel content)
- Share experiences with friends through a social feed
- Receive personalized recommendations through an intelligent algorithm 

## Dataset

- **Source**: Original survey created and distributed by the project team using Google Forms
- **Collection Period**: May 2025
- **Sample Size**: 54 respondents
- ***Limitations**: The relatively small sample size collected over a short period affects generalizability of findings*

The survey covered:
- Demographic information (age, gender, marital status, education, location, occupation)
- Technology usage (operating system)
- Entertainment consumption habits (days per week, hours spent on movies/series/games)
- Current usage of similar applications
- Opinion about the Unwind platform concept
- Intention to use and recommend the platform
- Feature preferences

## Project Structure

```

eda-entertainment-platform-survey/
├── data/
│   ├── processed/
│   └── raw/
├── images/
│   └── [visualization files]
├── notebooks/
│   ├── 01_data_preparation_and_cleaning.ipynb
│   ├── 02_univariate_analysis.ipynb
│   └── 03_eda.ipynb
├── venv/
├── .gitignore
├── LICENSE
├── requirements.txt
└── README.md

```

## Jupyter Notebooks

| Step | Notebook | Description |
| ---- | -------- | ----------- |
| **1. Data Preparation** | [01_data_preparation_and_cleaning.ipynb](notebooks/01_data_preparation_and_cleaning.ipynb) | Imports survey data, cleans and transforms variables, handles outliers, and prepares dataset for analysis. |
| **2. Univariate Analysis** | [02_univariate_analysis.ipynb](notebooks/02_univariate_analysis.ipynb) | As explicitly required by the academic project guidelines, each variable is individually analyzed to provide a complete characterization of the dataset before proceeding to relationship analysis. |
| **3. Exploratory Analysis** | [03_eda.ipynb](notebooks/03_eda.ipynb) | Explores relationships between variables, identifies patterns and insights, with focus on platform adoption drivers. |


## Installation

To set up the project locally:

```bash
git clone https://github.com/Gomes-Gustavo/eda-entertainment-platform-survey.git
cd eda-entertainment-platform-survey
pip install -r requirements.txt
```

## Author

Developed by Gustavo Gomes

- [LinkedIn](https://www.linkedin.com/in/gustavo-alves-gomes/)
