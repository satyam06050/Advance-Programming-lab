| Q.No | Task                                | Technique Used         | Function / Keyword                                  | 1-Line Explanation                                                |
| ---- | ----------------------------------- | ---------------------- | --------------------------------------------------- | ----------------------------------------------------------------- |
| 1    | Import dataset                      | Data Loading           | `pd.read_csv()`                                     | Reads the CSV file into a Pandas DataFrame.                       |
| 2    | Count rows & columns                | Shape inspection       | `df.shape`                                          | Returns tuple (rows, columns) of dataset.                         |
| 2    | First 10 rows                       | Preview data           | `df.head(10)`                                       | Displays first 10 rows of DataFrame.                              |
| 2    | Last 15 rows                        | Preview data           | `df.tail(15)`                                       | Displays last 15 rows of DataFrame.                               |
| 3    | Highest/Lowest salary by Gender     | Grouping + Aggregation | `groupby()` + `idxmax()` / `idxmin()`               | Finds row index of max/min salary within each gender group.       |
| 4    | Highest & Lowest salary overall     | Aggregation            | `idxmax()` / `idxmin()`                             | Returns index of highest and lowest salary row.                   |
| 5    | Fill missing Salary by Service mean | Conditional Imputation | `groupby('service').transform('mean')` + `fillna()` | Replaces missing salaries with mean salary of same service group. |
| 6    | Fill missing PhD by Service mean    | Conditional Imputation | `groupby('service')['phd'].transform('mean')`       | Replaces missing phd values using mean service-based grouping.    |
| 7    | Count Male & Female                 | Value Counting         | `value_counts()`                                    | Counts occurrences of each gender.                                |
| 7    | Pie chart (Gender)                  | Visualization          | `plt.pie()`                                         | Creates pie chart of gender distribution.                         |
| 8    | Count Professor Types               | Categorical Count      | `value_counts()`                                    | Counts Prof, AssocProf, AsstProf occurrences.                     |
| 8    | Pie chart (Rank)                    | Visualization          | `plt.pie()`                                         | Creates pie chart of rank distribution.                           |
| 9    | Senior most employee                | Maximum value          | `df['service'].idxmax()`                            | Finds employee with highest service years.                        |
| 9    | Junior most employee                | Minimum value          | `df['service'].idxmin()`                            | Finds employee with lowest service years.                         |
| 10   | Salary Histogram                    | Data Binning           | `plt.hist(bins=range(50000, max, 15000))`           | Creates histogram with bins starting 50K and step 15K.            |
