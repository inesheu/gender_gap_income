# Gender Pay Gap Analysis — Paraguay

This project analyzes income disparities by gender across occupations using official data from Paraguay’s Instituto Nacional de Estadísticas (INE).

## Columns Used

- `P06` (`gender`): Gender code (1 = Men, 6 = Women)
- `E01AIMDE` (`main_monthly_income`): Monthly income in Guaraníes
- `anoest` (`years_of_study`): Years of education
- `CATE_PEA` (`occupation_category`): Occupation code as string

## Occupation Codes

| Code | Occupation Label            |
|-------|----------------------------|
| '1'   | Public employee / worker   |
| '2'   | Private employee / worker  |
| '3'   | Employer or boss           |
| '4'   | Self-employed worker       |
| '5'   | Unpaid family worker       |
| '6'   | Domestic worker            |

Codes such as `9` (NR), `NA`, and `Blanco` are excluded.

## Purpose

To provide clear, data-driven insights that reveal the persistent gender pay gap in Paraguay, encouraging informed discussion and action.
