# Automobile Exploratory Data Analysis (EDA)

Welcome to my Automobile EDA project! This repository contains an in-depth analysis of the `automobile.txt` dataset, exploring key attributes like price, fuel economy, engine capacity, and manufacturer diversity. Built during my HyperionDev Data Science Bootcamp (98% average), this project showcases my skills in data cleaning, analysis, and visualization using Python, Pandas, Matplotlib, and Seaborn.

## Project Overview
This EDA investigates the automobile dataset to uncover trends and insights, answering questions like:
- Which cars are the most expensive?
- How do fuel efficiency and engine size compare between expensive and cheap cars?
- Which manufacturer builds the most fuel-efficient vehicles?
- Which vehicles have the largest engine capacity?
- Which manufacturer has the most car models?

## Dataset
- **Source**: `automobile.txt` (205 records, 26 columns initially).
- **Cleaning**: Removed duplicates, handled missing values, and converted data types (e.g., price, MPG, engine-size to int64).
- **Final State**: 24 columns post-cleaning (e.g., after dropping `normalized-losses`, `symboling`).

## Visualizations
The project includes five key visualizations, saved as PNG files in the `images/` folder:
1. **Top 5 Expensive Cars**: Highlights the priciest vehicles (e.g., Mercedes-Benz at $45,400).
2. **Average Fuel Economy: Most vs. Least Expensive Cars**: Compares MPG for top 5 vs. bottom 5 priced cars.
3. **Average Fuel Economy by Vehicle Manufacturer**: Ranks manufacturers by average MPG (e.g., Chevrolet at 43.7 MPG).
4. **Top 5 Vehicles with Largest Engine Capacity**: Showcases largest engines (e.g., Jaguar at 326 cc).
5. **Number of Car Models by Manufacturer**: Displays model counts (e.g., Toyota at 32 models).

## Setup Instructions
1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/automobile-eda.git.

2. **Install Dependencies**:
   ```bash
   pip install pandas numpy seaborn matplotlib

3. **Run the notebook**:
   ```bash
   jupyter notebook automobile_eda.ipynb

## Skills Demonstrated
- Data Cleaning: Handling missing data, duplicates, and type conversion.
- Data Analysis: Statistical insights using Pandas and NumPy.
- Visualization: Custom plots with Matplotlib and Seaborn.
- Version Control: Managed with Git.

