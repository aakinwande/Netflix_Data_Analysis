# Netflix Data Analysis Project
This project focuses on Data Analysis using Python, addressing various questions with Python commands and libraries. It serves as a comprehensive example of data analysis techniques applied to Netflix datasets.


<h1>Key Libraries</h1>

Pandas: Data manipulation, cleaning, and analysis.
Seaborn: Data visualization with attractive charts.


<h1>Data Exploration Functions</h1>

Explore initial data structure: head(), tail(), shape, dtypes, info().
Analyze categorical data: value_counts(), nunique().
Identify duplicates: duplicated().
Handle missing values: isnull(), dropna().
Filter data: .isin(), str.contains().
Work with dates/times: to_datetime(), dt.year.value_counts().
Group data: groupby().
Create visualizations: sns.countplot().


<h1>Data Analysis Tasks</h1>

Duplicate Removal:

Check for duplicates (e.g., df.duplicated()).
Remove duplicates (e.g., df.drop_duplicates()).
Null Value Exploration:

Count missing values per column (e.g., df.isnull().sum()).
Visualize missing value patterns with heatmaps (e.g., Seaborn).
Decide on handling strategies (removal, imputation).
"House of Cards" Info:

Filter for title (e.g., df[df['Title'] == 'House of Cards']).
Extract show ID and director.
Peak Release Year:

Group by release year (e.g., df.groupby('Release Year')).
Count releases per year (e.g., .size() or .count()).
Visualize distribution (e.g., sns.countplot()).
Movie/TV Show Breakdown:

Count categories (e.g., df['Category'].value_counts()).
Visualize counts (e.g., sns.countplot()).
Top 10 Directors:

Group by director (e.g., df.groupby('Director')).
Count releases per director (e.g., .size() or .count()).
Sort and select top 10 directors.
Filtering by Category, Type, and Country:

Use boolean indexing and logical operators (AND, OR) to filter based on conditions (e.g., category, type, country).
