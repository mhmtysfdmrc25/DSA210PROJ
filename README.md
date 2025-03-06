# Analysis of Temporal Changes in Spotify Listening Habits During Exam Periods

## Project Overview

This project examines how students' Spotify listening habits fluctuate during different periods, with a particular focus on stressful times such as exam periods. Music consumption is often influenced by external factors such as academic deadlines, workload intensity, and emotional state. By correlating students' Spotify listening history with exam dates sourced from a Notion calendar, this study aims to uncover how listening patterns and music preferences adapt during exam periods.

Spotify has become an essential platform for students, serving as a source of relaxation, concentration, and motivation. During exam periods, students may exhibit distinct listening behaviors—turning to instrumental music for focus, calming tracks for stress relief, or upbeat music for motivation. This project seeks to answer key questions such as:

- Does music listening time increase or decrease during exam periods?
- What genres are most frequently listened to during exams compared to non-exam periods?
- Do students tend to listen to songs with higher or lower BPM (beats per minute) during exam periods?

By integrating Spotify streaming history with structured exam date data from Notion, we aim to identify trends, correlations, and behavioral patterns. The findings could provide insights into the relationship between academic stress and music consumption, contributing to a broader understanding of how students use music as a coping mechanism during exams.

The project will employ data science techniques such as exploratory data analysis (EDA), sentiment analysis of track lyrics and moods, and visualization of listening habits. The results will be presented in interactive dashboards, highlighting the differences in listening behaviors between exam and non-exam periods. Ultimately, this project aspires to reveal meaningful patterns in student behavior and contribute to the study of music consumption under stress.

# Motivation

Understanding how external factors, such as exams, influence music consumption can provide deeper insights into emotional regulation, concentration strategies, and stress management techniques. Exam periods are often associated with increased cognitive load and altered daily routines, which can significantly impact listening habits.

This project aims to uncover how students' music preferences and listening intensity change during such periods. By analyzing data from both Spotify and Notion, we seek to identify trends that can improve self-awareness, enhance study strategies, and optimize music recommendations for focus and relaxation. The insights could also be useful for designing personalized study playlists or stress-reducing interventions tailored to individual needs during high-pressure periods.

# Data Sources

**Spotify Listening History:**  

- Obtained via Spotify API.

- Includes metadata such as track titles, artists, genres, timestamps, and listening durations.

- Requires OAuth authentication for user-specific streaming history.

**Exam Dates:**

- Extracted from a Notion calendar using Notion API.

- Provides structured data on exam schedules to correlate with listening habits.

# Objectives

- Analyze temporal listening patterns to determine how exam and non-exam periods differ in terms of listening intensity and duration.
- Examine genre preferences during exam periods compared to regular periods to identify shifts in music selection.
- Perform sentiment analysis on song lyrics and metadata to explore emotional patterns in music choices during different periods.
- Investigate the relationship between listening habits and stress-related periods, such as the tendency to listen to instrumental vs. vocal tracks or upbeat vs. slow-tempo music.
- Visualize all findings through charts and dashboards to effectively communicate the insights gained from the analysis.

# Tools and Techniques

  **Programming:** Python (Google Colab)

  **Libraries:**

    - pandas for data processing

    - matplotlib and seaborn for visualization

    - spotipy for Spotify API integration

    - TextBlob or VADER for sentiment analysis of song lyrics

  **Data Source Integration:**

    - Spotify API for streaming history

    - Notion API for exam schedules

  **Version Control:**  GitHub for project documentation and code sharing

# Expected Outcomes

This analysis will provide a detailed perspective on how students' Spotify listening habits evolve during exam periods compared to regular periods. 
We expect to uncover:

- Variations in listening duration, such as increased or decreased music consumption during exams.

- Shifts in genre preferences, such as a preference for instrumental, classical, or lo-fi beats for concentration.

- Emotional patterns in music consumption, highlighting changes in the mood (e.g., calming, energetic, melancholic) of tracks listened to during stressful periods.

Visualizations will clearly communicate these findings, offering actionable insights into how external factors like exams shape digital habits. The final deliverables will include a set of interactive dashboards and a comprehensive report hosted on GitHub, providing a robust analysis of the interplay between stress, time management, and music consumption.

# Limitations and Future Work

- The analysis is limited to metadata and does not include insights from physiological responses to music or real-time stress levels.

- Sentiment analysis of music relies on available metadata, lyrics, and pre-defined mood classifications, which may not always capture the full emotional impact of a song.

- Future work could expand the scope by incorporating biometric data (e.g., heart rate variability) to establish a stronger connection between music listening and stress levels. Additionally, integrating additional contextual data such as study duration or social interactions could provide a more comprehensive understanding of listening behaviors during exams.

- A predictive model could be developed to forecast listening habits during upcoming exam periods and suggest personalized music recommendations based on past behaviors.

