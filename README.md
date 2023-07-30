# v-lookup Description
This code provides a simple interactive tool to read a CSV file, filter it based on selected values from an Excel file (Filter page), and then display the unique values in a specified column for those selected values. The tool is implemented using Python with the help of the pandas library for data manipulation and ipywidgets for creating an interactive user interface in Jupyter Notebook or JupyterLab.
# Prerequisites:
- Python 3.x
- Jupyter Notebook or JupyterLab
- pandas library (installed via pip install pandas)
- ipywidgets library (installed via pip install ipywidgets)
# Usage:
- Make sure you have Python installed along with the required libraries (pandas and ipywidgets).
- Copy the code provided in the code snippet and paste it into your Jupyter Notebook or JupyterLab.
- Update the file paths and column names in the code with your actual data.
# Functions:
## read_selected_values_from_excel(excel_file_path, column_name):
- This function takes the path of an Excel file (excel_file_path) and the name of the column containing the list of selected values (column_name).
- It reads the Excel file and returns a list of selected values.
## display_unique_values(csv_file, column_name, selected_values, output_file):
- This function takes the path of the CSV file to be filtered (csv_file), the name of the column to filter on (column_name), the list of selected values obtained from the Excel file (selected_values), and the path for the output CSV file (output_file) where the filtered data will be saved.
- The function filters the CSV data based on the selected values, finds the unique values in the specified column, and then displays them.
- Additionally, it saves the filtered data into a new CSV file specified by output_file.
# How to Use:
- Provide the path of the CSV file (csv_file_path) that you want to filter. This is the CSV file from which data will be extracted based on selected values.
- Specify the name of the column to filter on (column_name_to_check). For example, if you want to filter based on product names, provide the column name that contains product names.
- Set the output CSV file path (output_csv_file) where the filtered data will be saved after applying the filter.
- Provide the path of the Excel file (excel_file_path) that contains the list of selected values (Filter page path).
- Specify the column name (excel_column_name) from which you want to read the selected values.
# Using the Tool:
- The user interface will show input fields for CSV File Path, Column Name, Output CSV File Path, and Excel File (Filter Page) Path.
- Enter the required file paths and column names in their respective input fields.
- Click the "Run" button to execute the code.
- The tool will read the selected values from the Excel file, filter the CSV data based on those values, and display the unique values in the specified column for those values.
- The filtered data will be saved to the output CSV file specified.
