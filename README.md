# Titanic EDA, Data Cleaning, and Visualization

## Overview
This project performs **Exploratory Data Analysis (EDA)**, data cleaning, and visualization on the Titanic dataset. It demonstrates practical steps for handling missing data, converting data types, generating insights, and visualizing trends, using Python's `pandas` and `matplotlib` libraries.

## Objectives
- Explore the classic Titanic dataset.
- Identify and handle missing values.
- Convert data types for accurate analysis.
- Generate summary statistics and group-based insights (e.g., survival rates by gender and class).
- Visualize key patterns and correlations.

## Dataset
The dataset includes passenger details such as:
- Passenger ID, Name, Age, Sex, Ticket, Fare
- Passenger Class (`Pclass`)
- Cabin and Embarked port
- Survival status (`Survived`)

Data is split into:
- **train.csv** — Used for analysis and model building.
- **test.csv** — Used for validation or future prediction tasks.

## Tools & Libraries
- **Python** (3.x)
- **pandas** — Data manipulation and cleaning
- **numpy** — Numerical operations
- **matplotlib** — Data visualization

## Project Workflow
1. **Load Data**  
   Read CSV files into Pandas DataFrames (`train` and `test`).

2. **Initial Inspection**  
   - View shapes, column types, and sample rows.
   - Summarize missing values.

3. **Data Cleaning**  
   - Handle missing values in `Age`, `Cabin`, and `Embarked`.
   - Convert categorical variables into numerical form when needed.
   - Ensure correct data types.

4. **Exploratory Data Analysis**  
   - Summary statistics (mean, median, mode).
   - Grouped survival analysis (e.g., by `Sex`, `Pclass`).
   - Visual exploration of distributions and relationships.

5. **Visualization**  
   - Bar charts and histograms.
   - Survival rate comparisons.
   - Correlation heatmaps (optional).

## How to Run
1. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib
