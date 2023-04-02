# Loan Application - Module 2 Challenge

The analyst was tsked with creating a command line interface (CLI) data processing application for bank loan pre-qualification screening.  The application gathers a series of input data, then matches applicable banks and loans to the inputs.

To input the data, the applicant is presented with a series of queries on their financial and credit history.  The applicant will input credit score, current debt level, income, the size of the loan desired, and the value of the applicant's home value.  The inputted data is compared against the daily_rate_sheet dataset, applicable banks and loans are presented to the applicant, and the application then has the choice to save that presented data into a CSV file.


---

## Technologies

This analysis was based in Python 3.7, and used the following libraries:
- sys - System-specific parameters and functions
- pathlib - Object-oriented filesystem paths
- csv - File Reading and Writing
- fire - For the command line interface, help page, and entrypoint.
- questionary - For interactive user prompts and dialogs

---

## Installation Guide

Prior to running the application, the following libraries must be installed:

![libraries.png]()

---

## Usage

To use the loan application, one must clone the git repository and run the following code in the command line:
    
    "python app.py"

When prompted, the applicant must input data for a series of questions for the application to run, then they will decide whether they would like to save the resulting data to a CSV:

![app.png]()

---

## Contributors

Instructor:
>Vinicio De Sola

Code References (Save CSV Function):
>[Python Write CSV File](https://www.pythontutorial.net/python-basics/python-write-csv-file/)

---

