## Tools Used
- **Language:** Python
- **Library:** Pandas
- **Environment:** Jupyter Notebook

## Cleaning Process
I performed the following steps to clean the raw dataset:

1. **Data Inspection:**
   - Checked for null values and duplicates.
   - Identified columns with incorrect data types (specifically dates).

2. **Handling Missing Values:**
   - [Explain what you did here. Example: Found 0 missing values, so no rows were dropped.]

3. **Standardization:**
   - Renamed all columns to lowercase with underscores for consistency (e.g., changed `ScheduledDay` to `scheduledday`).

4. **Data Type Conversion:**
   - Converted `scheduledday` and `appointmentday` from object (string) to `datetime` format to allow for time-based analysis.

5. **Duplicate Removal:**
   - Identified and removed [Number] duplicate rows to ensure data integrity.

## Final Output
- The clean dataset has been saved as `cleaned_dataset.csv`.
- The Python script is available in `Data_cleaning_task1.ipynb`.
