# Spotify Streaming History Analysis

## Overview
This project focuses on analyzing and visualizing Spotify streaming history data to gain insights into listening habits and preferences. The dataset used for this analysis contains detailed information about the user's listening history, including the date, time, artist, track, and duration of each played song.

## Motivation
The goal of this project is to explore the patterns and trends within the user's Spotify streaming history and extract meaningful insights. By analyzing the data, we aim to answer questions such as:

- What are the user's most frequently listened to artists and tracks?
- Are there any noticeable patterns in listening habits, such as specific time periods or days of the week when the user listens to music the most?
- Can we identify any favorite genres or music styles based on the user's listening history?
- How has the user's listening behavior changed over time?

## Data Source
The data used for this analysis was obtained from the Spotify streaming history feature, which provides users with a downloadable dataset containing their listening history. The dataset is in JSON format and includes information such as track name, artist, album, and timestamp.

## Tools and Libraries Used
- Python 3.8
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn

## Project Structure
- `data`: This folder contains the Spotify streaming history data file (`spotify_streaming_history.json`).
- `notebooks`: This folder contains the Jupyter Notebook files used for data analysis and visualization.
  - `1_data_preprocessing.ipynb`: Notebook for preprocessing the raw data, cleaning, and transforming it into a suitable format for analysis.
  - `2_exploratory_data_analysis.ipynb`: Notebook for performing exploratory data analysis, generating visualizations, and extracting insights from the data.
- `graph`: This folder contains the visualizations generated during the analysis, including charts, graphs, and plots.
- `README.md`: The main readme file for this project.


## Conclusion
This project provides a comprehensive analysis of Spotify streaming history data, uncovering valuable insights into listening habits, preferences, and trends. By analyzing the data and visualizing the results, we gain a better understanding of the user's music choices and patterns, which can be useful for personalization, recommendation systems, and further research in the field of music analysis.

## Future Work
- Perform sentiment analysis on the user's listening history to determine the overall mood or emotions associated with different tracks.
- Incorporate external data sources, such as song popularity or genre classification, to enhance the analysis.
- Build a recommendation system based on the user's listening history and preferences.

## Acknowledgments
- The Spotify streaming history feature for providing users with access to their listening data.
- The Pandas, Matplotlib, and Seaborn libraries for enabling data analysis and visualization in Python.
- The open-source community for sharing valuable resources and tutorials related to data analysis and visualization.

## Insights
![Word cloud of top 100 songs](https://github.com/Sawrav-23/Spotify-Streaming-History-Analysis/assets/144011738/e195d24d-dbbb-4e76-bee7-f2cf02e6e09a)
![Word cloud of top 100 artists](https://github.com/Sawrav-23/Spotify-Streaming-History-Analysis/assets/144011738/bbd7a211-3732-42a1-832c-e8ae2255ac32)
![weekend vs weekdays](https://github.com/Sawrav-23/Spotify-Streaming-History-Analysis/assets/144011738/4926afab-950f-46f4-96bb-cf5c4b1a4878)
![Unique songs](https://github.com/Sawrav-23/Spotify-Streaming-History-Analysis/assets/144011738/39530e10-dcb2-4c8f-8c35-bef661e87111)
![unique artists](https://github.com/Sawrav-23/Spotify-Streaming-History-Analysis/assets/144011738/a1ed5867-d5c0-463d-b9b2-6dcf5e437fd2)
![Top 10 fav songs](https://github.com/Sawrav-23/Spotify-Streaming-History-Analysis/assets/144011738/48aba4fb-208d-4dd5-a61c-fef1a21ab8f1)
![Top 10 fav artists based on counts](https://github.com/Sawrav-23/Spotify-Streaming-History-Analysis/assets/144011738/d7a1b929-330b-4b05-8def-edbce152f881)
![Top 10 fav artist based on hours](https://github.com/Sawrav-23/Spotify-Streaming-History-Analysis/assets/144011738/f64cba1e-9502-43ce-8638-f59550fb0b17)
![max number of songs played in a day](https://github.com/Sawrav-23/Spotify-Streaming-History-Analysis/assets/144011738/e9ff51f1-fef1-471c-8fae-abe88d47fe84)
![Heatmap of spotify usage](https://github.com/Sawrav-23/Spotify-Streaming-History-Analysis/assets/144011738/fbb25498-6d3b-4517-a98b-9de018beaa4c)
![Day wise spotify usage](https://github.com/Sawrav-23/Spotify-Streaming-History-Analysis/assets/144011738/07baa66c-4a0b-4904-8a63-c317b9a3efee)
![Average spotify usage over week](https://github.com/Sawrav-23/Spotify-Streaming-History-Analysis/assets/144011738/1e87a08e-35f3-4c37-b4c3-4e8600ac0516)
![Average spotify usage over the years](https://github.com/Sawrav-23/Spotify-Streaming-History-Analysis/assets/144011738/afadd6e9-2964-4c01-8fc9-4658fdddc89d)
![Average distribution of streaming](https://github.com/Sawrav-23/Spotify-Streaming-History-Analysis/assets/144011738/1d8a04ef-b949-449e-b10a-784cc02aba18)

