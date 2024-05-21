# Netflix Data Analysis Project
This project focuses on Data Analysis using Python, addressing various questions with Python commands and libraries. It serves as a comprehensive example of data analysis techniques applied to Netflix datasets.


<h1>Key Libraries</h1>

Pandas: Data manipulation, cleaning, and analysis.
Seaborn: Data visualization with attractive charts.


<h1>Data Exploration Functions</h1>

Explore initial data structure: head(), tail(), shape, dtypes, info().<br />
Analyze categorical data: value_counts(), nunique().<br />
Identify duplicates: duplicated().<br />
Handle missing values: isnull(), dropna().<br />
Filter data: .isin(), str.contains().<br />
Work with dates/times: to_datetime(), dt.year.value_counts().<br />
Group data: groupby().<br />
Create visualizations: sns.countplot().<br />


<h1>Data Analysis Tasks</h1>

Duplicate Removal:<br />
Check for duplicates (e.g., df.duplicated()).<br />
Remove duplicates (e.g., df.drop_duplicates()).<br />


Null Value Exploration:<br />
Count missing values per column (e.g., df.isnull().sum()).<br />
Visualize missing value patterns with heatmaps (e.g., Seaborn).<br />
Decide on handling strategies (removal, imputation).<br />

Peak Release Year:<br />
Group by release year (e.g., df.groupby('Release Year')).<br />
Count releases per year (e.g., .size() or .count()).<br />
Visualize distribution (e.g., sns.countplot()).<br />


Movie/TV Show Breakdown:<br />
Count categories (e.g., df['Category'].value_counts()).<br />
Visualize counts (e.g., sns.countplot()).<br />


Top 10 Directors:<br />
Group by director (e.g., df.groupby('Director')).<br />
Count releases per director (e.g., .size() or .count()).<br />
Sort and select top 10 directors.<br />


Filtering by Category, Type, and Country:<br />
Use boolean indexing and logical operators (AND, OR) to filter based on conditions (e.g., category, type, country).
