# Analysis of YouTube Viewing Habits During Exam Periods

## Project Overview

This project examines how students' YouTube viewing habits change during exam periods. Media consumption often reflects external factors such as academic deadlines, stress levels, and daily routines. By correlating YouTube watch history with exam dates sourced from a Notion calendar, this study aims to uncover how students' viewing patterns and content preferences adapt during these times.

YouTube plays a crucial role in both education and entertainment, serving as a source of relaxation and academic support. During exam periods, students may exhibit unique viewing behaviors—either consuming more educational content for study purposes or watching entertainment videos as a form of stress relief. This project seeks to answer key questions such as:

- Does YouTube watch time increase or decrease during exam periods?
- What types of videos are watched more frequently—educational, entertainment, or motivational content?
- Do students tend to watch shorter or longer videos during stressful times?
- Are there shifts in the emotional tone of the videos consumed?

By combining YouTube watch history with structured exam schedule data from Notion, this study aims to identify trends, patterns, and correlations in content consumption. The findings could provide insights into how stress and academic workload influence digital habits, potentially informing better time management strategies.

The project will employ data science techniques such as exploratory data analysis (EDA), sentiment analysis, and content categorization to process and visualize the data. Results will be presented in interactive charts and dashboards, highlighting the differences in viewing habits between exam and non-exam periods.

# Motivation

Understanding the impact of external factors, such as exams, on media consumption can provide insights into time management, emotional states, and stress-coping mechanisms. Exam periods are often linked to increased stress and changes in daily routines, which may significantly affect digital consumption habits.

By analyzing YouTube watch history alongside exam schedules, this project aims to uncover behavioral patterns that could help students improve self-awareness, manage stress effectively, and balance time spent on productive and relaxing activities. The findings could also contribute to personalized study recommendations or behavioral models tailored to external conditions.

# Data Sources

**YouTube Watch History:**  

- Obtained via Google Takeout.

- Includes metadata such as video titles, watch timestamps, and durations.

**Exam Dates:**

- Extracted from a Notion calendar using Notion API.

- Provides structured data on exam schedules to correlate with Youtube viewing habits.

# Objectives

- Analyze temporal viewing patterns to determine how YouTube usage varies between exam and non-exam periods.
- Examine the types of videos watched (e.g., educational, entertainment, motivational) during exam periods to identify shifts in content preferences.
- Investigate whether students watch shorter or longer videos during stressful periods.
- Perform sentiment analysis on video titles and descriptions to explore emotional patterns in content consumption.
- Visualize findings through charts and dashboards to effectively communicate insights.
  
## Tools and Techniques

  **Programming:** Python (Google Colab)

  **Libraries:**

    - `pandas` for data processing

    - `matplotlib` and `seaborn` for visualization

    - `spotipy` for Spotify API integration

    - `TextBlob` or `VADER` for sentiment analysis 

  **Data Source Integration:**

    - Google Takeout for YouTube watch history

    - Notion API for exam schedules

  **Version Control:**  GitHub for project documentation and code sharing

# Expected Outcomes

This analysis will provide insights into how YouTube viewing habits evolve during exam periods compared to regular periods. 
Expected findings include:

- Variations in viewing intensity, such as increased or decreased activity during exams.

- Shifts in content preferences, like a higher consumption of educational videos for study purposes or entertainment videos for stress relief.

- Differences in video duration preferences, potentially indicating shorter or longer content consumption based on stress levels.

- Emotional tone shifts in video consumption, detected through sentiment analysis of video titles and descriptions.

Visualizations will effectively communicate these insights, offering a data-driven perspective on how external factors like exams influence media consumption habits. The final deliverables will include interactive dashboards and a comprehensive report hosted on GitHub.

# Limitations and Future Work

- The analysis relies on metadata from YouTube watch history, without access to full video content or transcripts.

- Sentiment analysis depends on video titles and descriptions, which may not always reflect the actual content of the videos.

- Future work could incorporate physiological stress indicators (e.g., sleep patterns) to better correlate media consumption with stress levels.

- Further studies could extend the analysis to other forms of digital consumption, such as reading habits or online course engagement.

