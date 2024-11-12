# NVIDIA Financial Data Analysis

## Overview
This repository contains a Python Jupyter Notebook designed to extract, clean, and prepare financial data for NVIDIA Corporation from Yahoo Finance. The project uses Selenium for web scraping and Pandas for data manipulation, with the goal of creating clean CSV files ready for financial modeling and analysis in tools like Tableau.

## Key Features:
Extracts Income Statement, Balance Sheet, and Cash Flow data.
Cleans and reshapes the data for easy analysis.
Converts financial values (e.g., trillions to billions).
Replaces "TTM" with the current date for consistency.
Outputs clean CSV files ready for visualization in Tableau.

## Prerequisites
To run this project, you need:

Python 3.8 or higher
Chrome browser

The following Python packages:
selenium
pandas
nbformat (for managing Jupyter Notebook files)

## Installation

### Clone the Repository:
git clone https://github.com/vemendez/yahoo_finance_webscrap.git
cd NVIDIA-Financial-Analysis

### Install Required Python Packages:
pip install selenium pandas nbformat
Set Up ChromeDriver:

### Download the ChromeDriver that matches your Chrome browser version from here.
Place it in your PATH or in the project directory.

## Usage

Open the Jupyter Notebook using the following command:
jupyter notebook FinModel_Documented.ipynb
The notebook is divided into three main sections:

Income Statement Extraction: Scrapes NVIDIA’s income statement from Yahoo Finance and cleans the data.
Balance Sheet Extraction: Retrieves the balance sheet data, processes it, and outputs a clean CSV file.
Cash Flow Extraction: Collects cash flow data, cleans it, and prepares it for analysis.

## Output Files
The notebook generates the following cleaned CSV files:

nvidia_income_statement_clean_updated.csv: Income statement data with "TTM" replaced by today's date.
nvidia_balance_sheet.csv: Cleaned balance sheet data.
nvidia_cash_flow.csv: Cleaned cash flow data.
nvidia_valuation_measures_clean.csv: Valuation measures with trillions converted to billions.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements
Data sourced from Yahoo Finance.
Python web scraping made possible using Selenium.

## Contact
For any questions or issues, please contact:

Victor Mendez - https://www.linkedin.com/in/victor-eduardo-mendez-mba-798646174/
