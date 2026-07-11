# NYC Public School SAT Performance Analysis

Exploratory analysis of NYC public school SAT results, answering three questions about math performance, overall SAT rankings, and score variability across boroughs.

## Dataset

`schools.csv` — NYC public school records including:
- `school_name`
- `borough`
- `average_math`, `average_reading`, `average_writing` (average SAT section scores)

## Questions Answered

1. **Which schools have the best math results?**
   Filtered for schools scoring at or above 80% of the maximum possible math score (640/800), ranked from highest to lowest.

2. **What are the top 10 performing schools based on combined SAT scores?**
   Created a `total_SAT` column (sum of math, reading, and writing averages) and ranked all schools by it.

3. **Which borough has the largest standard deviation in combined SAT performance?**
   Grouped schools by borough and calculated the count, mean, and standard deviation of `total_SAT` per borough, then identified the borough with the highest variability.

## Tools

- Python
- pandas

## Files

- [`notebook.ipynb`](./notebook.ipynb) — full analysis with code and outputs
- `schools.csv` — source dataset (not included in repo; add your own copy or a data source link here)

