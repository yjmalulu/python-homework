# Financial Analysis with Python

**This Python script analyzes a company's financial records from a CSV file and generates a summary of key metrics.**

## Features

- Calculates total months, net profit/loss, average change in profit/loss, and greatest increase/decrease in profits.
- Prints analysis to the terminal.
- Exports results to a text file.

## Technologies Used

- Python 3.x
- pathlib library for file path handling
- csv library for reading CSV data

## Usage

1. Clone this repository.
2. Ensure the `budget_data.csv` file is in the same directory as the script.
3. Run the script from your terminal: `python financial_analysis.py`

## Output

The script will print the financial analysis to the terminal and create a `results.txt` file with the same information.

## Example Output
Financial Analysis
Total Months: 86
Total: $38382578
Average Change: $-2315.12
Greatest Increase in Profits: Feb-2012 (1926159)
Greatest Decrease in Profits:Sep−2013 (-2196167)
