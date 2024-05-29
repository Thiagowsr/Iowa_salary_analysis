This project aims to analyze Iowa's salary book since the fiscal year 2007, with the objective of understanding the evolution of salaries across various departments over the years. Additionally, it seeks to examine the salary distribution based on gender and state of residence.

Dataset

The dataset used in this analysis is the “State_of_Iowa_Salary_Book.csv”. It contains the name, gender, county or city of residence (when possible), official title, total salary received during each fiscal year, base salary for the employee, and traveling and subsistence expense reimbursed to state personnel beginning with Fiscal Year 2007.

Code

The code provided performs the following steps:
1.	Imported the required libraries, including pandas for data manipulation and plotly, dash and seaborn for 
2.	Loaded the dataset using the read_csv() function from pandas.
3.	Display the first few rows of the dataset using the head() function.
4.	Exploratory data analysis (EDA) was performed on the dataset.
5.	The column "State" was created based on the dictionary "city_to_state_dict".
6.	Performed an analysis by department, gender and state.
