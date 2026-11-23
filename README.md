# Student Performance Analysis

Class project analyzing student performance data with Python in Google Colab.

## Dataset

`xAPI-Edu-Data.csv` - educational records for 480 students with 17 attributes: demographics, engagement metrics (raised hands, visited resources, announcement views, discussion), attendance (StudentAbsenceDays), parent survey answers, and the final performance level (H / M / L).

## Tools

- Python (pandas, matplotlib) in Google Colab

## What I did

- Explored and validated the data (shape, column types, unique values, missing-value check)
- Looked at the distribution of performance levels (M: 211, H: 142, L: 127)
- Cross-tabulated attendance against performance level
- Compared average hand-raises across performance levels
- Visualized the results with matplotlib bar and pie charts

## Key findings

- Attendance is the clearest divider: of the students absent more than 7 days, 116 of 191 ended up in the low (L) group, while students absent under 7 days were mostly high or medium performers.
- Class participation tracks performance strongly: average hand-raises are about 70 for high performers versus about 17 for low performers.
- Parent satisfaction with the school: 292 Good vs 188 Bad.

## Files

- `Training Center Data Analysis.ipynb` - the full analysis notebook
- `xAPI-Edu-Data.csv` - the dataset used in the notebook
