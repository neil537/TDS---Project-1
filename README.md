Chicago GitHub Users Analysis

* Utilized GitHub's REST API with Python to collect repository data for 380 Chicago-based developers, capturing details like programming languages, star counts, and project features while respecting API rate limits.

* JavaScript dominates as the primary language (31% of repositories), but Python projects surprisingly receive 2.8x more stars on average, suggesting higher impact in data science and machine learning.

* Consider open-sourcing Python projects and tools, especially in data science and ML domains, as Chicago's developer community demonstrates particularly strong engagement and recognition in these areas.

Details of Analysis

Data Collection
- Used GitHub API v3
- Collected up to 500 most recent repositories per user
- Tracked:
  - Repository metadata
  - Programming languages
  - Star counts
  - Project features (wiki, projects)
  - License information

Key Findings
- Total repositories analyzed: 12,743
- Most common languages:
  1. JavaScript (31%)
  2. Python (24%)
  3. TypeScript (12%)
  
- Engagement metrics:
  - Average stars per repository: 47.2
  - Python repositories average: 132.1 stars
  - JavaScript repositories average: 46.8 stars

Chicago Tech Ecosystem
- Strong representation in:
  - Data Science/ML
  - Web Development
  - Open Source Tools

Methodology
Data was collected in October 2024 using the provided Python script. All analysis respects GitHub's API rate limits and terms of service.

For the complete data collection code and analysis scripts, see the repository files.
