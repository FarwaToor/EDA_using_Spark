# Spark Starter Kit - EDA on Netflix TV Shows & Movies Dataset
## Overview
This project focuses on performing Exploratory Data Analysis (EDA) on the Netflix TV Shows & Movies dataset using Apache Spark. The task is implemented using Python scripts running on Spark with Docker. The dataset contains details about TV shows and movies available on Netflix, and the goal is to analyze and visualize the data to uncover insights.

## Technologies Used
- Apache Spark: Used for distributed data processing and EDA.
- Python: Scala or Python is used for writing Spark programs.
- Docker: Spark is run in a Docker container to set up a controlled environment.
- Netflix TV Shows & Movies Dataset: The dataset used for EDA.

#### Run the EDA Script:
Open the notebook or script that applies the EDA process on the dataset (in Python).
The EDA will cover:
- Overview of the dataset.
- Data cleaning (handling missing values, duplicates).
- Data visualizations (distribution of genres, rating analysis, etc.).
- Insights based on the analysis.
- View Results: Once the script completes execution, you will see the EDA results and visualizations that provide insights into the Netflix dataset.

#### Dataset Information
The dataset includes the following columns:

- show_id: Unique identifier for each show.
- type: Type of content (Movie or TV Show).
- title: Title of the show.
- director: Director of the show.
- cast: Main cast of the show.
- country: Country where the show was produced.
- date_added: Date when the show was added to Netflix.
- release_year: Year the show was released.
- rating: Rating of the show.
- duration: Duration of the show (for movies, in minutes; for TV shows, in number of seasons).
- genre: Genre of the show.
- description: Description of the show.
  
### Conclusion
In this project, we have used Spark to perform a comprehensive EDA on the Netflix TV Shows & Movies dataset. The results include insights such as the distribution of genres, the number of movies vs TV shows, and missing values in the dataset.
