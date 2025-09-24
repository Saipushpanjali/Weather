I downaloaded the data from kaggle(https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset?utm_source=chatgpt.com) and performed these tasks in google colab.

1. Load and Inspect Data

Loaded the dataset with Pandas (pd.read_csv).
Checked shape, columns, and previewed first rows.
Looked for missing values.


2. Data Cleaning

Converted budget, revenue, runtime, and ratings columns to numeric (invalid values → NaN → filled with 0).
Extracted release_year from release_date.
Extracted main_genre from the JSON-like genres column using ast.literal_eval.


3. Statistical Analysis with NumPy

Computed mean, median, and standard deviation for:

Ratings (vote_average)
Budget
Revenue


4. Grouped Analysis with Pandas

By Genre: Calculated average rating per main_genre.
By Director: (if available) average rating per director.
By Year: Grouped by release_year to see rating trends over time.


5. Visualizations with Matplotlib

Bar Plot: Average rating by genre.
Line Plot: Average ratings across years.
Scatter Plots:
Budget vs Rating
Revenue vs Rating
Horizontal Bar Plot: Top-rated movies by rating.


-------------------------------------------------------------------------------------------------------------------------------------------------------------
