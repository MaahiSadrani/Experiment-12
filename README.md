# Experiment-12:
# Aim:
To perform categorical data analysis using Python.
# Theory:
Categorical Data Analysis involves analyzing data that can be divided into groups or categories
(such as Gender, Grade, Department, etc.). Unlike numerical data, categorical data focuses on labels and classifications rather than continuous values.
Python has powerful libraryies such as Pandas which provides efficient tools to analyze such data quickly and effectively.
We perform the following categorical data analysis.
Step 1: Reading Data
pd.read_csv()-Loads data from a CSV file into a DataFrame.
- Used to import the dataset for analysis.
Steo 2: Frequency Count
value_counts()-Counts occurrences of each category in a column.
- Helps understand how often each category appears.
Example: Number of students in each grade.
Step 3: Percentage Distribution
value_counts(normalize=True)*100
Converts frequency counts into percentages.
- Shows relative proportion instead of absolute count.
Step 4: Cross Tabulation
pd.crosstab(col1, col2)
Creates a table showing relationships between two categorical variables.
→ Useful for comparing categories like Gender vs Grade.
normalize='index'
Converts values into row-wise percentages.
→ Helps analyze distribution within each group.
Step 5: Grouping Data
groupby()
Groups data based on a column and applies functions.
→ Used for multi-level analysis like Department-wise Grade counts.
value_counts() with groupby
Provides counts within grouped categories.
Step 6: Filtering Data
df[df['column'] == value]
Extracts rows that meet a condition.
- Example: Selecting only Electronics orders.
Step 7: Sorting Data
sort_values(by='column')
Sorts dataset based on a column.
- Helps organize data for better understanding.
Step 8: Unique Values
unique()
Returns all distinct values in a column.
nunique()
Returns the count of unique values.
Step 9: Creating DataFrame
pd.DataFrame(data)
Converts dictionary data into tabular format.
- Used to create a dataset manually.
# Applications of Categorical Data Analysis:
- Student performance analysis
- Customer behavior analysis
- Market research
- Business decision-making
# Conclusion:
Categorical Data Analysis using Python is an effective way to interpret and summarize non-numerical data. 
By using functions like value_counts(), crosstab(), and groupby(), we can extract meaningful insights such as trends,relationships,
and distributions within the dataset.
<img width="390" height="696" alt="Screenshot 2026-04-18 130017" src="https://github.com/user-attachments/assets/18d8709c-f55b-49d4-872e-8d82aadabb41" />
<img width="318" height="485" alt="Screenshot 2026-04-18 130008" src="https://github.com/user-attachments/assets/a2aef71e-3167-4014-8a8c-e2054d14bb1b" />


