# FaultyExcel

This is a simple Python script for data analysis: turning faulty Excel dataset containing information in one column only (this specific one is about beekeeping organizations in the USA), and sort it into a tidy sheet

## Getting Started

To use this script, you will need to have Python 3.x installed on your computer along with the pandas and numpy libraries.

## Installation

1. Install Python 3.x on your computer by downloading it from the official Python website (https://www.python.org/downloads/).

2. Install the pandas and numpy libraries by running the following commands in your command prompt or terminal:

   ```
   pip install pandas
   pip install numpy
   ```

## Usage

1. Download the Excel dataset containing the beekeeping organizations information and save it in the same directory as the script.

2. Open the Python script in your text editor or IDE.

3. Edit the script to replace the file paths in the `pd.read_excel()` function with the path to your dataset.

4. Run the script.

## Functionality

The script does the following:

1. Reads in the Excel dataset.

2. Extracts information from the dataset, including the state, organization, and contact name(can be replaced for what necessery).

3. Sorts the data by state.

4. Separates the contact name and email address.

5. Removes any rows that do not contain an organization.

6. Outputs the cleaned data as a new Excel file.

## Future Work

This script can be extended in the following ways:

- Adding more functionality to the data cleaning process, such as removing duplicates or filling in missing data.

- Adding data visualization to the script to better understand the trends and patterns in the dataset.

- Automating the data download process from a web source.
