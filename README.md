# Compass Analytics Sports Analytics Hackathon User Guide In collaboration with Databricks
## Friday, October 13, 2023

### Table of Contents
1. [Context and Preamble Description](#context-and-preamble-description)
2. [File Descriptions](#file-descriptions)
3. [Data Description](#data-description)
4. [Data Dictionary](#data-dictionary)
5. [Hackathon Goal](#hackathon-goal)
6. [Guidance for Different Profiles](#guidance-for-different-profiles)
    - [Data Engineering](#data-engineering)
    - [Data Analyst](#data-analyst)
    - [Data Scientist](#data-scientist)
7. [Submission Outputs](#submission-outputs)
8. [Evaluation Criteria](#evaluation-criteria)
9. [Quick Links and Reference](#quick-links-and-reference)

---

## Context and Preamble Description
You're a novice in an NBA fantasy league competing against seasoned NBA enthusiasts. With limited basketball knowledge, you aim to predict last quarter score margins using data science and statistical analysis. Leveraging historical NBA play-by-play data from 1996 to 2023, you seek to gain a competitive edge in the league.

## File Descriptions
- **Play_by_play_YYYY-YY.parquet:** Contains all play-by-play data for the specified season.
- **Example_game_data.xlsx:** Sample game data for reference.

## Data Description
- Each file contains play-by-play data for the specified season, comprising both play-by-play and game-level data.

## Data Dictionary
- **Data_Dictionary_Hackathon.xlsx:** Provides detailed information for each step of the hackathon process.

## Hackathon Goal
The goal is to predict NBA score margins effectively for the 2022-2023 season using historical data. Participants will gain experience across all aspects of analysis from the perspectives of a data engineer, data analyst, and data scientist.

## Guidance for Different Profiles

### Data Engineering
- Objective: Migrate raw Parquet data files from an S3 bucket to Delta Live Tables within Unity Catalog in Databricks.
- Tasks: Ingest data, perform data cleaning, and aggregate data for downstream analysis.

### Data Analyst
- Objective: Create SQL queries to build datasets and develop a lakehouse dashboard to derive insights into player stats, team stats, and seasonal trends.

### Data Scientist
- Objective: Perform exploratory data analysis, create reusable datasets with feature engineering, and employ various regression modeling techniques to predict NBA score margins.

## Submission Outputs
- **Data Engineer:** Notebook containing Delta Live Table Pipeline for data migration.
- **Data Analyst:** Lakehouse Dashboard with visualizations of Gold Level Data for Insights.
- **Data Scientist:** Notebook(s) containing exploratory data analysis, regression modeling, and visualizations of actual vs. predicted results.

## Evaluation Criteria
Submissions will be evaluated on the following components:
- **Data Engineering:** Bronze table built, silver table built, gold tables built.
- **Data Analyst:** Use of SQL queries, descriptive/exploratory dashboard built, creativity, user experience.
- **Data Scientist:** Lowest MAE (Mean Absolute Error), bonus points for additional features.

## Quick Links and Reference
- [Spark Documentation](https://spark.apache.org/docs/latest/api/python/reference/index.html)
- [Pandas on Spark](https://spark.apache.org/docs/latest/api/python/user_guide/pandas_on_spark/index.html)
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Scikit-Learn Documentation](https://scikit-learn.org/stable/modules/classes.html)
- [Unity Catalog Documentation](https://docs.databricks.com/en/data-governance/unity-catalog/index.html)
- [Delta Live Tables Documentation](https://docs.databricks.com/en/delta-live-tables/index.html)
- [Lakehouse Dashboard Documentation](https://docs.databricks.com/en/dashboards/lakeview.html)
