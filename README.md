# Product Comparison Tool

## Description
The objective of this code was to compare the number of products listed in an Excel file with those in an XML file. Initially, the data from the Excel file needed to be integrated with a CSV file using a unique identifier. The "check_count.ipynb" file verifies whether the total count of products grouped by specific attributes is identical between the XML and Excel files. The "check_extended.ipynb" file examines whether all products share the same attributes in both files. Additionally, certain products are required to be eliminated from the dataframe generated from the Excel file. Ultimately, a CSV file containing the analysis results is generated.

## Files
- `check_count.ipynb`:  Tool for comparing the count of grouped products.
- "check_extended.ipynb": Tool for comparing products and their attributes.

## Requirements
To run this tool, make sure you have the following packages installed:
- lxml
- pandas
- tqdm
- os

## Usage
1. Prepare Excel and XML files and ensure that the Excel file and XML file are in the correct format and located in the same directory as the code files.
2. Import the required packages.
3. Run the "check_count.ipynb" file to check if the number of products is the same in both files. This will provide a summary of the total count of products in each file.
4. Run the "check_extended.ipynb" file to compare the attributes of the products in the Excel and XML files. This will identify any differences in the attributes of the shared products.
5. Both tools will generate a CSV file containing the results of the analysis.

## Contributors
Agnieszka Chilimoniuk
 
