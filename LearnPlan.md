# Pandas Functions - Complete and Categorized

This file categorizes and lists essential **Pandas functions** to help track my learning journey and serve as a quick reference.

---

## **1. Data Inspection and Exploration**

| Function          | Description                                                  |
|-------------------|--------------------------------------------------------------|
| `head()`          | View the first few rows of a DataFrame.                      |
| `tail()`          | View the last few rows of a DataFrame.                       |
| `info()`          | Display a summary of the DataFrame.                          |
| `describe()`      | Get statistical summaries of numeric columns.                |
| `sample()`        | Randomly sample rows or columns.                             |
| `shape`           | Get the number of rows and columns in a DataFrame.           |
| `columns`         | Access or modify column names.                               |
| `index`           | Access or modify the index (row labels).                     |
| `dtypes`          | Get data types of each column.                               |
| `memory_usage()`  | Check memory usage of a DataFrame.                           |

---

## **2. Handling Missing Data**

| Function          | Description                                                  |
|-------------------|--------------------------------------------------------------|
| `isnull()`        | Check for missing values in the DataFrame.                   |
| `notnull()`       | Check for non-missing values.                                |
| `fillna()`        | Fill missing values with a specified value.                  |
| `dropna()`        | Remove rows or columns with missing values.                  |
| `interpolate()`   | Fill missing values using interpolation methods.             |

---

## **3. Data Selection and Filtering**

| Function          | Description                                                  |
|-------------------|--------------------------------------------------------------|
| `loc[]`           | Access rows and columns by labels.                           |
| `iloc[]`          | Access rows and columns by integer indices.                  |
| `at[]`            | Access a single value by row and column labels.              |
| `iat[]`           | Access a single value by row and column indices.             |
| `query()`         | Filter DataFrame rows using a query string.                  |

---

## **4. Data Cleaning and Transformation**

| Function          | Description                                                  |
|-------------------|--------------------------------------------------------------|
| `rename()`        | Rename columns or rows.                                      |
| `replace()`       | Replace values in the DataFrame.                             |
| `astype()`        | Change the data type of a column.                            |
| `apply()`         | Apply a function to rows or columns.                         |
| `applymap()`      | Apply a function element-wise to the entire DataFrame.       |
| `map()`           | Apply a function element-wise to a Series.                   |
| `duplicated()`    | Find duplicate rows.                                         |
| `drop_duplicates()` | Remove duplicate rows.                                     |
| `clip()`          | Limit the values in a DataFrame to a specified range.        |

---

## **5. Sorting and Ranking**

| Function          | Description                                                  |
|-------------------|--------------------------------------------------------------|
| `sort_values()`   | Sort a DataFrame by a specific column.                       |
| `sort_index()`    | Sort a DataFrame by its index.                               |
| `rank()`          | Assign ranks to entries based on their values.               |

---

## **6. Grouping and Aggregation**

| Function          | Description                                                  |
|-------------------|--------------------------------------------------------------|
| `groupby()`       | Group and aggregate data.                                    |
| `agg()`           | Apply multiple aggregation functions.                        |
| `transform()`     | Apply a function to each group and return a transformed DataFrame. |
| `pivot_table()`   | Create a pivot table to summarize data.                      |

---

## **7. Merging and Combining Data**

| Function          | Description                                                  |
|-------------------|--------------------------------------------------------------|
| `merge()`         | Combine DataFrames based on common columns or indices.       |
| `concat()`        | Concatenate DataFrames along a particular axis.              |
| `join()`          | Join DataFrames based on their indices.                      |
| `append()`        | Append rows of one DataFrame to another. (Deprecated in recent versions) |

---

## **8. Input and Output**

| Function          | Description                                                  |
|-------------------|--------------------------------------------------------------|
| `read_csv()`      | Read a CSV file into a DataFrame.                            |
| `read_excel()`    | Read an Excel file into a DataFrame.                         |
| `read_json()`     | Read a JSON file into a DataFrame.                           |
| `read_sql()`      | Read data from a SQL query or database into a DataFrame.     |
| `read_html()`     | Read HTML tables into a DataFrame.                           |
| `to_csv()`        | Write a DataFrame to a CSV file.                             |
| `to_excel()`      | Write a DataFrame to an Excel file.                          |
| `to_json()`       | Write a DataFrame to a JSON file.                            |
| `to_sql()`        | Write a DataFrame to a SQL table.                            |

---

## **9. Statistical and Mathematical Operations**

| Function          | Description                                                  |
|-------------------|--------------------------------------------------------------|
| `mean()`          | Calculate the mean of numeric columns.                       |
| `sum()`           | Calculate the sum of numeric columns.                        |
| `count()`         | Count non-missing values in each column.                     |
| `min()`           | Find the minimum value in each column.                       |
| `max()`           | Find the maximum value in each column.                       |
| `std()`           | Calculate the standard deviation.                            |
| `var()`           | Calculate the variance.                                      |
| `corr()`          | Calculate pairwise correlation between columns.              |
| `cov()`           | Calculate pairwise covariance between columns.               |
| `cumsum()`        | Compute the cumulative sum of numeric columns.               |
| `cumprod()`       | Compute the cumulative product of numeric columns.           |

---

## **10. Time Series Operations**

| Function          | Description                                                  |
|-------------------|--------------------------------------------------------------|
| `to_datetime()`   | Convert a column or Series to a datetime object.             |
| `resample()`      | Resample time series data to a different frequency.          |
| `rolling()`       | Perform rolling window calculations.                         |
| `expanding()`     | Perform expanding window calculations.                       |

---

## **How to Use This List**

- **Beginner**: Focus on **Data Inspection** and **Handling Missing Data** first.
- **Intermediate**: Explore **Grouping**, **Merging**, and **Statistical Operations**.
- **Advanced**: Dive into **Time Series** and **Custom Transformations**.

Feel free to contribute or suggest improvements as I continue my Pandas learning journey!


git add . && git commit -m "Your commit message here" && git push origin main
