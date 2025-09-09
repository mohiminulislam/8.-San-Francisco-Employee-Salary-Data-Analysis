# San Francisco City Employee Salary Data Analysis

This repository contains an analysis of salary and compensation data for San Francisco city employees. The dataset includes annual pay details from 2011 to 2014 and provides insights into employee compensation trends across different roles and years.

## Dataset Overview

The dataset includes information on:
- Employee names
- Job titles
- Various pay components including Base Pay, Overtime Pay, Other Pay, and Benefits
- Total Pay and Total Pay including Benefits
- Year of record
- Additional metadata such as employment status

The data is sourced from public city records and covers over 148,000 employee entries.

## Repository Contents

- `Salaries.csv` – Raw dataset file containing employee compensation data
- `database.sqlite` – SQLite database version of the dataset
- `research.ipynb` – Jupyter notebook with thorough data analysis and visualizations

## Project Description

This project explores:
- Trends in base pay, overtime, and total compensation over time
- Variations in pay by job title and department
- Distribution and statistics of employee salaries, including outliers
- Data cleaning and preprocessing steps such as handling missing values and type conversions
- Visual insights through charts and summary statistics

The goal is to gain a comprehensive understanding of the city’s payroll structure, highlight key compensation patterns, and support further data-driven decision making and research.

## Getting Started

### Prerequisites

- Python 3.7+
- Jupyter Notebook or JupyterLab
- Python libraries: pandas, numpy, matplotlib, seaborn

Install required packages via pip if not already installed:
```
pip install pandas numpy
```

### Running the Analysis

1. Clone the repository:
```
git clone https://github.com/Abhi0049k/San-Francisco-City-Employee-Salary-Data.git
cd San-Francisco-City-Employee-Salary-Data
```
2. Launch Jupyter Notebook and open the analysis notebook:
```
jupyter notebook research.ipynb
```
3. Follow the notebook cells to explore the data and analyses.

## Data Description

Key columns in the dataset include:

| Column Name       | Description                                  |
|-------------------|----------------------------------------------|
| EmployeeName      | Name of the employee                         |
| JobTitle          | Employee's job title                         |
| BasePay           | Base salary                                  |
| OvertimePay       | Pay for overtime hours worked                |
| OtherPay          | Additional compensations (e.g., awards)      |
| Benefits          | Monetary value of benefits                    |
| TotalPay          | Total pay without benefits                    |
| TotalPayBenefits  | Total pay including benefits                  |
| Year              | Year of the salary record                      |
| Status            | Employment status (Full-time or Part-time)    |

## Contributing

Contributions are welcome! Feel free to fork the repository, make improvements or add analyses, and submit pull requests.

## License

This project is for educational purposes. Please refer to the dataset's license on Kaggle for any restrictions on data usage.

---

**Author:** [Abhi0049k](https://github.com/Abhi0049k)