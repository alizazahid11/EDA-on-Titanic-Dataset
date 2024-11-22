

---

# Titanic Survival Analysis

This project analyzes the Titanic dataset to explore factors that influenced survival rates. It involves data exploration, cleaning, preprocessing, and exploratory data analysis (EDA) to uncover patterns and trends related to survival.

## Table of Contents
1. [Introduction](#introduction)  
2. [Features](#features)  
3. [Installation](#installation)  
4. [Usage](#usage)  
5. [Dataset Overview](#dataset-overview)  
6. [Tasks Performed](#tasks-performed)  
7. [Results and Visualizations](#results-and-visualizations)  
8. [Contributing](#contributing)  
9. [License](#license)

---

## Introduction

The Titanic disaster is one of the most infamous shipwrecks in history. This project aims to analyze the Titanic dataset to identify trends and factors that affected passenger survival. By exploring and preprocessing the dataset, we can extract meaningful insights and prepare the data for predictive modeling.

---

## Features

- **Data Exploration**:  
  - Inspect dataset structure and distributions.  
  - Identify correlations between features and survival.  

- **Data Cleaning and Preprocessing**:  
  - Handle missing values in `Age`, `Cabin`, and `Embarked`.  
  - Encode categorical features (`Sex` and `Embarked`).  
  - Create new features like `FamilySize` from `SibSp` and `Parch`.  

- **Exploratory Data Analysis (EDA)**:  
  - Visualize survival trends across various features such as gender, age, and class.  
  - Uncover patterns that may predict survival.

- **Visualizations**:  
  - Generate clear and insightful plots to enhance understanding of the dataset.

---

## Installation

1. Clone this repository to your local machine:
   ```bash
   git clone <repository_url>
   cd titanic-survival-analysis
   ```

2. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```

---

## Usage

1. Open the Jupyter Notebook or Python script provided in the repository.  
2. Run the code step-by-step to explore, preprocess, and analyze the dataset.  
3. Modify the code to test new hypotheses or visualize additional trends.  

---

## Dataset Overview

The Titanic dataset contains information about passengers, including demographics, ticket details, and survival status.  

Key features include:  
- **Survival**: Survival indicator (0 = No, 1 = Yes).  
- **Pclass**: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd).  
- **Sex**: Gender of the passenger.  
- **Age**: Age of the passenger.  
- **SibSp**: Number of siblings/spouses aboard.  
- **Parch**: Number of parents/children aboard.  
- **Fare**: Ticket fare.  
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).  

---

## Tasks Performed

### 1. Data Exploration  
- Inspected dataset structure and statistical summaries.  
- Identified missing values and distribution patterns in key features.

### 2. Data Cleaning and Preprocessing  
- Filled missing values in `Age` using median imputation.  
- Imputed missing `Embarked` values with the most frequent port.  
- Encoded `Sex` and `Embarked` features into numeric format.  
- Created new feature `FamilySize` by combining `SibSp` and `Parch`.  

### 3. Exploratory Data Analysis (EDA)  
- Analyzed survival rates by:  
  - Gender: Higher survival rates for females.  
  - Class: First-class passengers had a higher chance of survival.  
  - Age: Children had better survival rates compared to adults.  
- Created visualizations to highlight these trends.

---

## Results and Visualizations

### Key Insights:
1. **Gender**: Female passengers had significantly higher survival rates.  
2. **Class**: Survival rates were highest among first-class passengers.  
3. **Age**: Younger passengers (children) were more likely to survive.  

### Visualizations:
- Survival rates by gender, age groups, and passenger class.  
- Distribution of ticket fares across survival statuses.  
- Heatmaps showcasing feature correlations.  

Sample visualizations can be found in the repository.

---

## Contributing

Contributions are welcome! If you have suggestions for improvement or new analysis techniques, feel free to open an issue or submit a pull request.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

