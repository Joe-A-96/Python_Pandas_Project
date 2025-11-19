# Core Pandas Skills

## 📘 1. Importing & Exploring Data
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
<img width="348" height="126" alt="image" src="https://github.com/user-attachments/assets/61919a02-636d-4cbe-a4cc-408b493f03ee" />

## 3. Boolean Logic & Filtering
- Create boolean masks from conditions
- Combine logical operators:
  - `&` — AND
  - `|` — OR
- Apply masks to filter DataFrame rows
<img width="633" height="151" alt="image" src="https://github.com/user-attachments/assets/b887132d-76fe-4a2f-91a2-ee8e41865c6e" />

## 4. Avoiding Chained Assignment Issues
- Use `.copy()` when creating filtered DataFrames
- Understand why `.copy()` prevents assignment warnings and unexpected behavior
<img width="397" height="68" alt="image" src="https://github.com/user-attachments/assets/0fb5f10e-b338-4a95-afa0-817b858d83a5" />

## 5. Sorting & Organizing Data
- Sort DataFrames with:
  - `.sort_values(by='column')`
  - Sorting by multiple columns
- Use ascending or descending order as needed
<img width="700" height="291" alt="image" src="https://github.com/user-attachments/assets/0db2727a-0c25-4a90-8fb7-1275f386c179" />
