# Automated-Report-Generation
Python script that analyzes CSV data and generates a PDF report with statistics (average, max, min) and a data table.

**COMPANY**: CODETECH IT SOLUTIONS

**Name**: Siddharth Patel

**INTERN ID**: CT04DL819

**Domain**: Python Programming

**BATCH Duration**: 4 Weeks

**Mentor**: Neela Santhosh Kumar

**PROJECT**: AUTOMATED REPORT GENERATION

# Data Analysis and PDF Report Generator

## Overview

This Python project reads data from a CSV file, performs basic statistical analysis (average, maximum, minimum), and generates a professional PDF report with the analysis results and the original data in a table format.

## Features

- CSV data reading with error handling for numeric values
- Basic statistical analysis:
  - Average calculation
  - Maximum value identification
  - Minimum value identification
- PDF report generation with:
  - Title section
  - Analysis results section
  - Data table display
- Clean, modular code structure

## Requirements

- Python 3.x
- `fpdf` library (install with `pip install fpdf`)

## Usage

1. Prepare your data in a CSV file named `data.csv` with columns 'Name' and 'Value'
2. Run the script: `python task2.py`
3. The report will be generated as `report.pdf`

## Example CSV Format

```
Name,Value
James,35
Thomas,41
Rahul,11
Steve,50
Alex,49
```

## Output

The script produces a PDF report containing:
- Analysis summary (average, max, min values)
- Tabular display of all input data
![Screenshot 2025-05-03 185451](https://github.com/user-attachments/assets/2674ecec-9208-48d0-b60d-611085de26d9)


## Customization

You can easily modify:
- The input/output filenames in the `main()` function
- The PDF styling (fonts, colors, layout) in the `generate_pdf_report()` function

## License
- **This project**: [MIT License](LICENSE) - Free for any use  
