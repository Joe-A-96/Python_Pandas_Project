# Core Pandas Skills

##📘 1. Importing & Exploring Data
- Load CSV data using `pd.read_csv()`
- Inspect datasets with:
  - `.head()`
  - `.info()`
  - `.describe()`
- Understand dataset structure and column metadata

## 2. Working with DataFrames
- Select columns using:
  - `df['column']`
  - `df[['col1', 'col2']]`
- Use boolean indexing to select rows
- Count `True` values in a boolean Series using `.sum()`

## 3. Boolean Logic & Filtering
- Create boolean masks from conditions
- Combine logical operators:
  - `&` — AND
  - `|` — OR
- Apply masks to filter DataFrame rows

## 4. Avoiding Chained Assignment Issues
- Use `.copy()` when creating filtered DataFrames
- Understand why `.copy()` prevents assignment warnings and unexpected behavior

## 5. Sorting & Organizing Data
- Sort DataFrames with:
  - `.sort_values(by='column')`
  - Sorting by multiple columns
- Use ascending or descending order as needed
