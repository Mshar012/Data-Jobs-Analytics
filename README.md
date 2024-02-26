## Project: Data Jobs Analytics

### Overview

This GitHub repository contains a comprehensive data analysis project focused on exploring and visualizing trends in the job market within the data industry. The project utilizes Python and popular libraries like Pandas, Plotly, and Tabulate to perform data manipulation and create interactive visualizations.

### Project Structure

0. jobs_in_data.csv

The dataset comprises information about various jobs in the data industry, including job categories, salaries, experience levels, and employee residence. This dataset was sourced from Kaggle.

1. libraries.ipynb

This Jupyter Notebook file includes the importation of necessary libraries and packages required for the project. It ensures a clean and organized setup for subsequent analysis.

2. visualizations.ipynb

In this notebook, various visualizations are created to represent key insights from the dataset. The visualizations cover aspects such as average salary distribution, experience level counts, and geographical distribution of salaries.

3. main_analysis.ipynb

The main analysis notebook serves as the central point for executing the functions and creating an end-to-end data analysis workflow. It imports functions from libraries.ipynb and visualizations.ipynb to streamline the entire process.

### How to Use

Clone the repository to your local machine.
Open and run the main_analysis.ipynb notebook to execute the entire analysis pipeline.
Explore individual notebooks for specific functionalities.

### Dataset Setup

##### 1) Download Dataset:
Obtain the dataset, "jobs_in_data.csv," from the repository.
If you're using a different version of this dataset, make sure it's in CSV format.

##### 2) Update File Path:
If your dataset is not in the default location, adjust the file path in 'main_analysis.ipynb' to point to your dataset.

###### Example: Update the file path based on your dataset location
file_path = "path/to/your/dataset/jobs_in_data.csv"

###### Load the dataset
df = pd.read_csv(file_path)




### Dependencies

Python 3.x
Pandas
NumPy
Plotly
Tabulate

### Contributing

Feel free to contribute by suggesting improvements, reporting issues, or submitting pull requests. Your feedback is highly appreciated!
