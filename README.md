# Netflix_analysis
# Movie Dataset Analysis

## Overview
This project analyzes a dataset of movies to gain insights into trends such as genre popularity, vote distribution, and movie release patterns. The dataset was cleaned, processed, and visualized using Python libraries like Pandas, Seaborn, and Matplotlib.

## Dataset
The dataset contains the following columns:
- **Release_Date**: The release date of the movie.
- **Title**: Movie title.
- **Overview**: A brief synopsis of the movie.
- **Popularity**: Popularity score of the movie.
- **Vote_Count**: Number of votes the movie received.
- **Vote_Average**: Average rating of the movie.
- **Original_Language**: Language of the original movie release.
- **Genre**: Genre(s) of the movie.
- **Poster_Url**: URL of the movie poster.

## Data Preprocessing
1. **Handling Missing Data**: Rows with missing values were dropped.
2. **Extracting Year**: The `Release_Date` column was converted to datetime format and only the year was extracted.
3. **Categorizing Movies by Ratings**: Movies were classified into four categories based on `Vote_Average`:
   - Not Popular
   - Below Average
   - Average
   - Popular
4. **Splitting the Genre Column**: Since a movie can have multiple genres, the `Genre` column was split and exploded into separate rows.

## Analysis and Visualizations
1. **Most Frequent Movie Genres**: A count plot was used to visualize the most common genres.
2. **Vote Distribution**: A categorical plot showed how movies are rated.
3. **Most & Least Popular Movies**: Identified movies with the highest and lowest popularity scores.
4. **Movie Releases by Year**: A histogram displayed the distribution of movie releases over time.

## Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## How to Run
1. Clone the repository:
   ```sh
   git clone <repo-url>
   cd <repo-folder>
   ```
2. Install dependencies:
   ```sh
   pip install pandas matplotlib seaborn
   ```
3. Run the Jupyter Notebook to explore the analysis.

## Results
- The dataset contains a diverse range of genres, with some genres being more frequent.
- Most movies fall into the average rating category.
- Certain years saw higher movie releases compared to others.

## Future Improvements
- Include more advanced machine learning models to predict movie success.
- Expand dataset with more features such as director, budget, and revenue.

## License
This project is open-source and available under the MIT License.

