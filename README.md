# Paraguay Income Gender Gap Analysis

This repository contains Python code to analyze gender pay gaps using Paraguay’s INE survey data (2022-2025).

## Data Files

- CSV files are named with the format: `Trimester_Year.csv`
  - Example: `EPHC_1_2022.csv` means first trimester of 2022.
- Data covers multiple years and trimesters.

## Columns Used

| CSV Column | Description           | Alias in Code          |
|------------|-----------------------|-----------------------|
| P06        | Gender code           | `gender`              |
| E01AIMDE   | Main monthly income   | `main_monthly_income` |
| anoest     | Years of study        | `years_of_study`      |
| CATE_PEA   | Occupation category   | `occupation_category` |

## Occupation Category Codes

| Code | Description                 |
|-------|-----------------------------|
| 1     | Public employee / worker    |
| 2     | Private employee / worker   |
| 3     | Employer or boss            |
| 4     | Self-employed worker        |
| 5     | Unpaid family worker        |
| 6     | Domestic worker             |

*Codes like '9' (NR), 'NA', and 'Blanco' are excluded.*

## Usage

- Load and clean CSV data using the columns above.
- Use the provided code to analyze income by gender and occupation.
- Income values are processed and displayed in millions of Guaraníes.

## Source

Data comes from the [Instituto Nacional de Estadísticas (INE), Paraguay](https://www.ine.gov.py/).

---

*For full code and details, see the Python scripts in this repository.*
