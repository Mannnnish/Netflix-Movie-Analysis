Netflix Movie Analysis
📚 Project Overview
This Python project is focused on analyzing a Netflix movie dataset to uncover key insights regarding movie genres, ratings, popularity, and trends over time. Using Pandas, Matplotlib, and Seaborn, we clean the dataset, perform exploratory data analysis (EDA), and visualize key trends.

The analysis includes:

Genre distribution

Popularity trends

Highest and lowest-rated movies

Release year distribution

🔧 Tools & Libraries Used
Pandas: Data manipulation and cleaning

Matplotlib: Data visualization

Seaborn: Statistical data visualization

NumPy: Numerical operations

🧹 Data Cleaning
Fixing Data Types:

Convert Vote_Count and Vote_Average to numeric.

Convert Release_Date to datetime format.

Handling Missing Values:

Fill missing Release_Date values with 0 and cast to integer.

Drop unnecessary columns (Overview, Original_Language, Poster_Url).

Handle missing (NA) values by removing rows with missing data.

Exploding Genre Column:

Split the Genre column to separate individual genres and expand the data, resulting in a new dataset with more granular genre data.

📊 Key Insights
Most Frequent Genre:

Drama is the most frequent genre in the dataset, appearing in over 14% of the movies.

Genre with Highest Votes:

Drama also has the highest number of votes, with 25.5% of the dataset having popular votes.

Movie with Highest Popularity:

"Spider-Man: No Way Home" holds the highest popularity rating in the dataset and belongs to the Action, Adventure, and Science Fiction genres.

Movie with Lowest Popularity:

"The United States" and "Threads" have the lowest popularity ratings, with genres such as Music, Drama, War, Sci-Fi, and History.

Most Filmed Year:

2020 saw the highest number of movie releases in the dataset.
