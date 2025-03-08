# Analysis of ChatGPT Usage During Project Work and Exam Periods

## Project Overview

This project aims to analyze how my ChatGPT usage fluctuates during both project work periods and exam periods by correlating interaction data with timelines extracted from my Notion workspace. Effective project management and exam preparation often involve extensive research, brainstorming, and problem-solving, which can lead to increased reliance on AI tools like ChatGPT. By examining my ChatGPT usage before, during, and after these critical periods, this study seeks to uncover patterns in AI-assisted productivity and study habits.

ChatGPT serves as a powerful tool for ideation, content creation, technical problem-solving, and exam revision. However, its usage may vary depending on project complexity, exam difficulty, deadlines, and personal work habits. This project will investigate key questions such as:

- Does my ChatGPT usage increase during active project work periods?
- What types of questions or topics dominate my interactions with ChatGPT during project phases?
- Does my ChatGPT usage increase during exam periods?

By integrating ChatGPT interaction logs with structured project timelines and exam schedules from Notion, I aim to identify trends in how AI usage supports both academic and project workflows. The findings could provide valuable insights into AI-driven productivity patterns and highlight how external academic demands shape digital tool utilization.

The project will employ data science techniques such as exploratory data analysis (EDA), topic modeling, and temporal analysis to uncover trends and correlations. Results will be presented in interactive visualizations to illustrate usage fluctuations across different project and exam phases. Ultimately, this study seeks to enhance our understanding of AI-assisted study and work strategies, optimizing ChatGPT usage for more efficient learning and productivity.

# Motivation

Understanding how AI tools integrate into project workflows and exam preparation can provide deeper insights into productivity patterns, cognitive workload, and study habits. Both project work and exam periods typically involve fluctuating demands, requiring different levels of research, problem-solving, and revision at various stages.

This project aims to uncover whether ChatGPT serves as a critical support tool during these intensive academic periods. By analyzing usage trends, I hope to gain insights into how AI can be better leveraged for efficiency, idea generation, problem resolution, and study support. The findings could be useful for optimizing work and study strategies and identifying best practices for AI-assisted learning and productivity.

# Data Sources

**ChatGPT Interaction Logs:**  

- Extracted via OpenAI’s API usage data or local conversation logs.

- Includes metadata such as timestamps, query content, and response lengths.

**Exam Dates:**

- Extracted from a Notion calendar using Notion API.

- Provides structured data on exam dates to analyze study-related ChatGPT usage patterns.

**Project Timelines:**

- Extracted from Notion using the Notion API.

- Provides structured data on project start and end dates to correlate with ChatGPT activity.

# Objectives

- Analyze ChatGPT usage patterns before, during, and after both project work periods and exam periods to determine how AI-assisted research, brainstorming, and study evolve.
- Examine the types of queries made during active project and exam phases to identify dominant themes and problem areas.
- Investigate whether the frequency and complexity of questions increase as project deadlines and exams approach.
- Perform temporal analysis to detect peaks and lulls in ChatGPT interactions corresponding to project milestones and exam schedules.
- Visualize findings using interactive charts and dashboards to illustrate AI usage trends during different academic phases.
  
## Tools and Techniques

  **Programming:** Python (Google Colab)

  **Libraries:**

    - `pandas` for data processing

    - `matplotlib` and `seaborn` for visualization

    - `NLTK` or `spaCy` for text analysis and topic modeling

  **Data Source Integration:**

    - OpenAI API for ChatGPT logs

    - Notion API for project timelines and exam schedules

  **Version Control:**  GitHub for project documentation and code sharing

# Expected Outcomes

This analysis will provide a detailed perspective on how ChatGPT usage fluctuates throughout project work periods and exam periods. 
I expect to uncover:

- Variations in AI interaction intensity, such as increased usage during research-heavy phases, just before deadlines, and in the days leading up to exams.
- Shifts in question complexity and focus areas, showing how AI supports different aspects of both project work and academic study.
- Patterns in query types, such as a transition from broad ideation to specific problem-solving in project work and from conceptual understanding to direct question-solving in exam preparation.

The findings will be visualized in interactive dashboards, offering actionable insights into how AI can be optimally integrated into structured work and study periods. The final deliverables will include a comprehensive report and data visualizations hosted on GitHub, providing an analytical framework for improving AI-assisted productivity and study strategies.

# Limitations and Future Work

- The analysis relies on metadata and does not assess the quality or effectiveness of ChatGPT responses.

- Text analysis results depend on query structure and may not fully capture nuanced research and study behaviors.

- Future work could expand the study to include additional productivity metrics, such as time tracking or task completion rates, to provide a more holistic view of AI's role in work and study efficiency.

- Developing a predictive model to forecast ChatGPT usage patterns during upcoming projects and exams could enhance planning and workload management.

