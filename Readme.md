# Music Dataset Analysis Project 

## Overview 

This project involves an in-depth analysis of a music dataset, focusing on various aspects such as track popularity (streams), artist details, release periods, and audio features (e.g., danceability, energy). The analysis is done through data manipulation, statistical computations, and visualization using Python.

The goal is to uncover trends, patterns, and relationships between different music features and metrics such as streams. Various visualizations were created to make the insights easier to interpret.

## Features of the Project 

- **Data Cleaning**: Processed the dataset to remove unnecessary columns, handle missing values, and resolve duplicates. Performed transformations such as converting numeric months into month names and converting string values to integers.

- **Descriptive Statistics**: Generated descriptive statistics for key numerical columns, especially focusing on audio features like danceability and energy.

## Exploratory Data Analysis (EDA)

1. **Descriptive Statistics**: Descriptive statistics such as mean, median, and range were calculated for key numerical columns, especially audio features (e.g., danceability_%, energy_%).
2. **Value Counts**: For categorical columns like released_month and artist_count, `value_counts()` was used to examine how many unique values exist and their respective frequencies.
3. **Correlation Analysis**: Performed correlation analysis to identify relationships between variables.
4. **Visualizations**: Created visualizations to represent data insights.

## Data Visualization

- Histograms, bar charts, scatter plots, and pie charts for better understanding.
- Created pairplots and correlation heatmaps for numerical columns.
- Examined top tracks, artists, and release distributions.
- Scatter plots to explore relationships between streams and audio features (e.g., energy, speechiness).

## Visualizations

### Here are some of the key plots generated during the analysis:

1. **Top Tracks by Streams**: A bar chart displaying the top 7 most-streamed tracks.
2. **Monthly Release Distribution**: Bar chart representing the number of songs released each month.
3. **Artist Count Distribution**: A pie chart showing the proportion of tracks involving solo artists, duos, and groups.
4. **Scatter Plot**: Streams vs. energy to examine the correlation.
5. **Correlation Heatmap**: Exploring the relationships between audio features such as danceability, valence, and instrumentalness.
