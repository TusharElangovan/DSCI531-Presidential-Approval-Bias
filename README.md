# DSCI531-Presidential-Approval-Bias
# Assessing Bias in Presidential Approval Ratings

This repository contains the code and data for the project **"Assessing Bias in Presidential Approval Ratings: A Multivariate Analysis of Economic Indicators and Party Affiliation"**. The study investigates the relationship between U.S. economic performance and presidential approval ratings, with a focus on identifying partisan bias in public perception.

---

## Table of Contents
1. [Project Overview](#project-overview)
2. [Data Sources](#data-sources)
3. [Methodology](#methodology)
4. [Repository Structure](#repository-structure)
5. [Installation and Setup](#installation-and-setup)
6. [Usage](#usage)
7. [Results](#results)
8. [Contributing](#contributing)
9. [License](#license)

---

## Project Overview

Presidential approval ratings are a critical metric for assessing public sentiment toward the U.S. president. While economic indicators such as GDP growth, unemployment rates, inflation, and consumer confidence are often cited as key determinants of public approval, this study hypothesizes that partisan bias may skew approval ratings beyond objective economic conditions.

Using a multiple regression model, we analyze whether approval ratings are systematically influenced by the president’s political party, independent of economic performance. The findings aim to uncover potential biases in public perception and contribute to discussions on fairness in predictive modeling of political sentiment.

---

## Data Sources

The following datasets were used in this study:
1. **Economic Data**: Retrieved from the [Federal Reserve Economic Data (FRED)](https://fred.stlouisfed.org/).
   - GDP growth
   - Unemployment rates
   - Inflation rates
   - Consumer confidence indices
2. **Presidential Approval Ratings**: Retrieved from [Gallup News](https://news.gallup.com/poll/116677/presidential-approval-ratings-gallup-historical-statistics-trends.aspx).
3. **Additional Data**: Supplementary data on party affiliations and historical context were collected from publicly available sources.

---

## Methodology

The analysis involves the following steps:
1. **Data Collection**: Historical economic data and presidential approval ratings were retrieved from FRED and Gallup News.
2. **Data Preprocessing**: Cleaning and merging datasets to create a unified dataset for analysis.
3. **Regression Modeling**: A multiple regression model was developed to predict approval ratings based on economic indicators, controlling for the president’s party affiliation.
4. **Bias Evaluation**: Statistical tests and fairness-aware machine learning techniques were used to assess the influence of partisan bias on approval ratings.


---

## Installation and Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/presidential-approval-bias.git
   cd presidential-approval-bias
