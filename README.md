# Analysis of Argues with my Girlfriend on Exam Periods

## Project Overview

This project explores the argues with my gf in relation to external stressors, particularly on academic exam periods. Emotional dynamics in relationships can be influenced by various external factors, including workload, stress, lack of seeing each other and time constraints. By collecting and analyzing conflict-related data alongside exam schedules, this study aims to uncover trends and potential correlations between academic stress and relationship disagreements.

Long-term relationships often experience recurring periods of tension, and external stressors can act as triggers for conflicts. By recording conflict instances, causes, and durations, and integrating structured data from an academic calendar, this project seeks to answer key questions such as:

- Does the frequency of conflicts increase during exam periods?
- What are the primary triggers of conflicts, and do they vary between normal periods and exam weeks?
- How long do conflicts last, and is there a pattern in their resolution process?

By combining self-recorded relationship conflict data with structured exam schedule data, this project aims to identify behavioral patterns and stress-related triggers. The results could provide insights into stress management, relationship communication strategies, and emotional resilience during high-pressure periods.

# Motivation

Understanding how external factors, such as academic stress, impact personal relationships can offer valuable insights into emotional regulation and communication. Exam periods are known for increased anxiety and time constraints, which may influence interpersonal interactions and conflict likelihood.

This project seeks to explore the extent to which external stressors affect relationship dynamics and whether certain trends can be identified. The findings could help in developing strategies for fight management and stress reduction in both romantic and interpersonal relationships.

# Data Sources

**Manually Recorded Conflict Data:**  

- A self-maintained Excel sheet including (planning to gather by past and future WhatsApp conversations):

  - Date of the fight

  - Cause of the fight

  - Fight occurrence (1 = Yes, 0 = No)

  - Duration of the conflict (in days)

  - Solution status and method (1 = Solved, 0 = Unsolved, how it's solved if 1)
  
**Exam Dates:**

- Extracted from a Notion calendar using Notion API.

- Provides structured data on academic schedules for correlation analysis.

**WhatsApp Sentiment Data (Optional):**

- Message frequency and sentiment analysis to evaluate emotional tone.

- Categorization into positive, neutral, and negative messages for trend analysis.

# Objectives

- Analyze conflict frequency to determine if there is a significant increase during exam periods.
- Identify conflict triggers and assess if their nature changes during high-stress periods.
- Examine conflict resolution patterns to understand whether exam stress affects resolution time.
- Perform sentiment analysis on WhatsApp messages to identify emotional shifts leading to conflicts.
- Visualize findings through charts and dashboards to effectively communicate trends and patterns.
  
## Tools and Techniques

  **Programming:** Python (Google Colab)

  **Libraries:**

    - `pandas` for data processing

    - `matplotlib` and `seaborn` for visualization

    - `scipy.stats` for correlation analysis

    - `Vader` (or `TextBlob`) for sentiment analysis

  **Data Source Integration:**

    - Notion API for exam schedules

    - Manual data entry for conflict tracking on excel sheet

  **Version Control:**  GitHub for project documentation and code sharing

# Expected Outcomes

This project will provide a quantitative analysis of how relationship conflicts fluctuate in response to external stressors like exams. 
Expected findings include:

- Variations in conflict frequency between exam and non-exam periods.
- Identification of common triggers leading to disputes.
- Insights into conflict duration and resolution trends over time.
- Emotional patterns in WhatsApp conversations before and during conflicts.

Results will be visualized in interactive dashboards, offering a comprehensive view of stress-related relationship dynamics. The final deliverables will include data-driven insights hosted on GitHub, potentially leading to strategies for better emotional regulation during high-stress periods.

# Limitations and Future Work

- The analysis is based on self-reported data, which may introduce bias.

- WhatsApp sentiment analysis relies on text messages and may not fully capture the emotional depth of conflicts.

- Future work could integrate physiological data, such as heart rate variability, to assess emotional stress levels.

- A predictive model could be developed to anticipate potential conflicts based on stress indicators, allowing for proactive resolution strategies.


