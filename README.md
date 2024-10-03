# Netflix 1990s Movie Analysis

## Project Overview
This project focuses on analyzing movies released on Netflix during the 1990s. Using Python and key data analysis libraries, the project explores insights into movie durations, identifies short action movies, and visualizes trends in movie release patterns. The aim is to understand content trends in duration and genre during this decade.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Objectives](#objectives)
- [Methods and Analysis](#methods-and-analysis)
- [Visualizations](#visualizations)
- [Results](#results)
- [Challenges Faced](#challenges-faced)
- [Improvements](#improvements)
- [Potential Future Work](#potential-future-work)
- [Setup Instructions](#setup-instructions)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Dataset
The dataset used in this project includes Netflix content from a range of release years, with a focus on movies produced during the 1990s. The key columns from the dataset include:
- `show_id`: Unique identifier for each show.
- `type`: Whether the content is a movie or TV show.
- `title`: The title of the movie.
- `director`: Name of the director.
- `cast`: List of the main cast members.
- `country`: The country where the movie was produced.
- `release_year`: The year the movie was released.
- `duration`: The runtime of the movie in minutes.
- `genre`: Genre of the movie (Action, Comedy, Drama, etc.).
- `description`: Short description or synopsis of the movie.

## Objectives
The key objectives of this analysis are:
- To identify the most frequent movie duration for films released in the 1990s.
- To count the number of action movies lasting less than 90 minutes.
- To visualize key patterns, such as movie duration distribution and genre breakdown for short action movies.

## Methods and Analysis
The analysis involved the following steps:
1. **Data Filtering**: Filtering the dataset to extract only movies released between 1990 and 1999.
2. **Data Cleaning**: Ensuring the `duration` column is converted to a numeric format, as some entries may contain non-numeric values.
3. **Identifying Frequent Duration**: Using the mode of the `duration` column to find the most frequent movie length.
4. **Counting Short Action Movies**: Defining short movies as those with a runtime of less than 90 minutes and counting how many of these belong to the "Action" genre.
5. **Visualization**: Plotting visual insights such as the distribution of movie durations and genre distribution for short action movies.

## Visualizations
1. **Distribution of Movie Durations**: A histogram that shows the frequency of different movie durations for 1990s films, highlighting the most common duration.
2. **Genre Distribution of Short Action Movies**: A pie chart that shows how short action movies are distributed across different genres.
3. **Year-wise Release of Short Movies**: A bar chart that displays how short movies (under 90 minutes) were released each year during the 1990s.

## Results
- **Most Frequent Movie Duration**: The most frequent movie duration in the 1990s was approximately 94 minutes.
- **Short Action Movies**: There were 7 action movies with a runtime of less than 90 minutes.
- The distribution of movie durations shows that most films are longer than 90 minutes, but a significant portion falls within the short-movie category.
- Action films with a duration under 90 minutes were mostly categorized into other overlapping genres such as comedy or thriller.

## Challenges Faced
- **Data Cleaning**: Some rows in the dataset had non-numeric or missing values in the `duration` column, which had to be carefully handled to avoid errors in the analysis.
- **Genre Overlap**: Many movies had multiple genres listed, making it difficult to categorize movies strictly into a single genre like "Action."
- **Missing Data**: Some entries lacked key information, such as cast or director details, limiting the scope of deeper analysis.

## Improvements
- **Data Accuracy**: Future work could involve cross-checking the dataset with another movie database to improve the accuracy and fill in missing details (e.g., IMDB).
- **Additional Features**: Adding more visualizations for detailed breakdowns, such as actor-director collaborations or country-wise analysis.
- **Handling Multi-Genre Movies**: A more sophisticated approach could be used to categorize movies with multiple genres for more accurate genre-specific analysis.

## Potential Future Work
1. **Trend Analysis**: Perform a time series analysis on the evolution of movie durations over the decades and compare with other time periods.
2. **Genre Popularity**: Investigate how the popularity of different genres changed over time, especially in the 1990s, and how this might have influenced movie durations.
3. **Director-Based Insights**: Analyzing movies directed by specific prominent filmmakers from the 1990s to identify patterns in their work.
4. **Comparison to 2000s**: Comparing 1990s movie trends with those from the 2000s to identify shifts in movie lengths, genres, and other aspects.

## Setup Instructions
To run this project locally, follow these steps:

1. **Install Required Libraries**:
   Install the necessary Python libraries by running:
   bash
   pip install pandas matplotlib seaborn
