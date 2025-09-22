# Task-1-Data-Cleaning-and-Preprocessing
Data Cleaning and Preprocessing Internship Project in Python
# Steps 
| Missing values | Maybe some rows have blank `price` or `mileage`. If only a few, fill numeric missing with median. If price blank → maybe drop row.                  
| Duplicates     | Perhaps the same car entry appears twice (same VIN, owner, etc) → remove duplicates.                                                                  
| Text fields    | Car brand (“Toyota”, “toyota”, etc), car color (“Red”, “red”, “RED ”) → standardize. Conditions (“New”, “Used”, “used”, “second‑hand”) → make uniform. |
| Date fields    | If there is a sale date or listing date, ensure all dates follow same format.                                                                          
| Numeric fields | Price, odometer reading should be numbers; check for text formatted as numbers.                                                                        
| Outliers       | Price very high (maybe typo with extra zero) or mileage extremely high or low → flag.  
## Deliverables
- `Auto Sales data - Raw` → raw dataset with issues
- `Auto Sales data - Cleansed.xlsx` → cleaned dataset
- `summary_report.md` → this document
