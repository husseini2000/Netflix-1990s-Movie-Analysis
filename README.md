# Netflix 1990s Movies Analysis

## Overview

This project focuses on performing an exploratory data analysis (EDA) on Netflix movie data, specifically for movies released during the 1990s (1990-1999). The goal of this analysis is to uncover insights into movie durations, genre distribution, and trends related to short movies (under 90 minutes) during that decade. Various visualizations are created to help understand the data better.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Objectives](#objectives)
- [Steps of Analysis](#steps-of-analysis)
- [Visualizations](#visualizations)
- [Results](#results)
- [Challenges Faced](#challenges-faced)
- [Improvements](#improvements)
- [Potential Future Work](#potential-future-work)
- [Setup Instructions](#setup-instructions)
- [Technologies Used](#technologies-used)
- [Acknowledgments](#acknowledgments)

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

### Key Questions Answered:
1. **What was the most frequent movie duration in the 1990s?**
2. **How many short action movies (under 90 minutes) were released in the 1990s?**
3. **How are short action movies distributed across different genres?**
4. **What is the yearly release trend of short movies in the 1990s?**

## Steps of Analysis

1. **Data Loading**: Load the dataset and filter movies that were released between 1990 and 1999.
   
2. **Analysis & Visualizations**:
   - **Most Frequent Movie Duration**: Identified the most common movie duration using mode.
   - **Distribution of Movie Durations**: Visualized the distribution of movie durations using a histogram.
   - **Number of Short Action Movies**: Counted the short action movies (less than 90 minutes) released in the 1990s.
   - **Genre Distribution of Short Action Movies**: Displayed a pie chart showing how short action movies are distributed across different genres.
   - **Yearly Release of Short Movies**: Created a bar chart showing the number of short movies (under 90 minutes) released each year in the 1990s.

## Visualizations

### 1. **Distribution of Movie Durations**
   A histogram showing the frequency of different movie durations for 1990s films, with the most common duration highlighted.

### 2. **Genre Distribution of Short Action Movies**
   A pie chart displaying the distribution of short action movies across different genres.

### 3. **Yearly Release of Short Movies**
   A bar chart showing the number of short movies (under 90 minutes) released each year during the 1990s.

## Results
- **Most Frequent Movie Duration**: The most frequent movie duration in the 1990s was approximately 94 minutes.
- **Short Action Movies**: There were 7 action movies with a runtime of less than 90 minutes.
- The distribution of movie durations shows that most films are longer than 90 minutes, but a significant portion falls within the short-movie category.
- Action films with a duration under 90 minutes were mostly categorized into other overlapping genres such as comedy or thriller.

## Challenges Faced
- there are no challenges

## Improvements
- **Additional Features**: Adding more visualizations for detailed breakdowns, such as actor-director collaborations or country-wise analysis.

## Potential Future Work
1. **Trend Analysis**: Perform a time series analysis on the evolution of movie durations over the decades and compare with other time periods.
2. **Genre Popularity**: Investigate how the popularity of different genres changed over time, especially in the 1990s, and how this might have influenced movie durations.
3. **Director-Based Insights**: Analyzing movies directed by specific prominent filmmakers from the 1990s to identify patterns in their work.
4. **Comparison to 2000s**: Comparing 1990s movie trends with those from the 2000s to identify shifts in movie lengths, genres, and other aspects.

## Setup Instructions

1. Clone this repository:
    ```bash
    git clone https://github.com/husseini2000/Netflix-1990s-Movie-Analysis.git
    ```

2. Navigate to the project directory:
    ```bash
    cd Netflix-1990s-Movie-Analysis.git
    ```

3. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the Jupyter Notebook:
    ```bash
    jupyter notebook notebook.ipynb
    ```

## Technologies Used

- Python 3.x
- pandas
- matplotlib
- seaborn
- jupyter

## Acknowledgments

This project utilizes datasets from Kaggle. Special thanks to Kaggle for providing the data.

## Contact

Feel free to reach out if you have any questions or suggestions!

- **LinkedIn**: [Al-Husseini Abdelaleem](https://www.linkedin.com/in/al-husseiniabdelaleem)
- **GitHub**: [husseini2000](https://github.com/husseini2000)


