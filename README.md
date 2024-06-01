# Iowa Salary Analysis

This project aims to analyze Iowa's salary book since the fiscal year 2007, with the objective of understanding the evolution of salaries across various departments over the years. Additionally, it seeks to examine the salary distribution based on gender and state of residence.

## Dataset

The dataset used in this analysis is the “State_of_Iowa_Salary_Book.csv”. It contains the name, gender, county or city of residence (when possible), official title, total salary received during each fiscal year, base salary for the employee, and traveling and subsistence expense reimbursed to state personnel beginning with Fiscal Year 2007.

Resource of Dataset: https://data.iowa.gov/Government-Employees/State-of-Iowa-Salary-Book/s3p7-wy6w/about_data

Resource of dictionary: https://public.opendatasoft.com/explore/dataset/georef-united-states-of-america-county/table/?disjunctive.ste_code&disjunctive.ste_name&disjunctive.coty_code&disjunctive.coty_name&sort=year

## Code

The code provided performs the following steps:
1.	Imported the required libraries, including pandas for data manipulation and plotly, dash and seaborn for 
2.	Loaded the dataset using the read_csv() function from pandas.
3.	Display the first few rows of the dataset using the head() function.
4.	Exploratory data analysis (EDA) was performed on the dataset.
5.	The column "State" was created based on the dictionary "city_to_state_dict".
6.	Performed an analysis by department, gender and state.

## Usage
To use this code, you can follow these steps:

1. Make sure you have the required libraries installed.
2. Download the "State_of_Iowa_Salary_Book.csv" and "georef-united-states-of-america-county.csv" datasets from links above and place it in the directory "Data" in the same directory as the code file.
3. Open the code file and run it using a Python IDE or Jupyter Notebook.
