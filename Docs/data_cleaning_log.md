# Data Cleaning Log

## Project
Hospitality Business Intelligence & Revenue Analytics

## Dataset
Hotel Booking Demand Dataset

## Objective
Prepare the dataset for SQL analysis, EDA, and Power BI dashboard creation.

---

## Data Quality Assessment

### Tasks Completed

- Imported dataset
- Checked dataset dimensions
- Reviewed data types
- Identified missing values
- Checked duplicate records
- Inspected sensitive (PII) columns

---

## Cleaning Actions (To Be Performed)

- Remove PII columns
- Handle missing values
- Remove duplicate rows
- Correct data types if required
- Validate business rules
- Create derived features

## Cleaning Completed

### Removed Columns

- company (94.31% missing)
- name (PII)
- email (PII)
- phone-number (PII)
- credit_card (PII)

### Missing Value Treatment

- agent → Filled with 0
- country → Filled with "Unknown"
- children → Filled with 0

### Duplicate Records

- No duplicate rows detected

### Output

hotel_bookings_cleaned.csv
