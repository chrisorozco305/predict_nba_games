# NBA Game Winner Prediction

This project focuses on predicting the winners of NBA basketball games using a combination of web scraping, data preprocessing, and machine learning. It is an end-to-end project that showcases my skills in data extraction, data cleaning, and predictive modeling.

---

## Project Workflow

Here’s the step-by-step process I followed to complete the project:

1. **Scraped NBA Standings and Box Score Data**  
   - Collected game data from Basketball Reference using Python.  

2. **Cleaned HTML Data**  
   - Processed and cleaned the scraped HTML using BeautifulSoup to prepare it for analysis.  

3. **Parsed Box Scores into DataFrames**  
   - Transformed the cleaned data into structured pandas DataFrames suitable for machine learning.  

4. **Feature Selection**  
   - Analyzed the data to identify the most predictive features for determining game outcomes.  

5. **Trained a Machine Learning Model**  
   - Used scikit-learn to build and train predictive models for game winners.  

6. **Computed Rolling Predictors**  
   - Added rolling averages and dynamic predictors to improve the model's accuracy.  

---

## Code Overview

All code for this project is organized into three Jupyter notebooks:  

- **`get_data.ipynb`**: Scrapes box scores from Basketball Reference.  
- **`parse_data.ipynb`**: Cleans and processes the data into a pandas DataFrame.  
- **`predict.ipynb`**: Builds, trains, and evaluates machine learning models.   

---

## Prerequisites

To understand this project, you should be familiar with:  

- **Python Basics**: Functions, if-else statements, loops, and data structures.  
- **Data Cleaning**: Handling missing values and transforming raw data.  
- **Pandas**: Manipulating and analyzing data using pandas DataFrames.  
- **Machine Learning**: Basic understanding of model training and evaluation.  

---

## Installation and Setup

To run this project locally, ensure you have the following installed:  

- **Python 3.8+**  
- **JupyterLab**  

Additionally, install the required Python packages:  

```bash
pip install pandas scikit-learn beautifulsoup4 playwright
