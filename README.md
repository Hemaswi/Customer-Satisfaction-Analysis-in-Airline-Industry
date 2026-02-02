# Customer-Satisfaction-Analysis-in-Airline-Industry

## Project Overview
This project explores the key drivers of airline passenger satisfaction using descriptive analytics, predictive modeling, and clustering techniques. The aim is to identify which service features most strongly influence satisfaction, uncover behavioral patterns among different traveler segments, and provide actionable insights for improving customer experience.

The project uses the original dataset sourced form Kaggle and generates a cleaned dataset during the preprocessing stage. No additional dependencies are required beyond Python and standard data science libraries.

---

## Requirements
This project requires Python 3.x and standard libraries such as:
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  
- statsmodels  

All necessary libraries are already included in the `pyenv` file packaged with this submission.

---

## How to Run the Code

### Step 1: Place the Original Dataset
Ensure the original dataset is saved in the same directory as the notebook or script.  
filename: 'Invistico_Airline.csv'



### Step 2: Run the Notebook or Script
Open the provided notebook or Python script and run all cells from top to bottom.  
During execution, the code will:
- Load the original dataset  
- Clean and preprocess the data  
- Generate a cleaned dataset  
- Perform descriptive analytics  
- Build predictive models  
- Conduct clustering analysis  
- Produce visualizations and summaries  

### Step 3: Locate the Cleaned Dataset
After preprocessing, the script automatically saves a cleaned version of the dataset.  




If you need to regenerate this file, delete the existing version and rerun the code.

### Step 4: Re-run Analysis Using Cleaned Data
If preferred, you can modify the loading section of the notebook to load the cleaned dataset directly 'Invistico_Airline_cleaned.csv'.  
Once loaded, you may rerun the analysis steps without reprocessing the raw data.

---

## Outputs Generated
Running the code produces:
- Descriptive statistics and satisfaction distributions  
- Correlation visualizations  
- Logistic regression model results  
- Confusion matrix and classification report  
- K-means clustering outputs  
- Visual interpretations of passenger segments  
All outputs appear directly within the notebook.

---

## References
- Dataset sourced from Kaggle.com 
- Scikit-learn documentation  
- Statsmodels documentation  
- Academic literature on airline service quality and passenger satisfaction  

---

## Notes
This README accompanies the submitted `pynb` file, original dataset, cleaned dataset, and analysis code. It is meant to guide users on how to run the project and understand its components.
