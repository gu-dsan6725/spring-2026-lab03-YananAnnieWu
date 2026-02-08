# Data Quality Rules

## Data Validation

- Always check for missing values before any analysis
- Always check for duplicate rows and report them

## Data Integrity

- Always log the shape of any DataFrame after loading or transforming it
- Never drop rows without logging how many were removed and why

## Data Handling

- Always use polars instead of pandas