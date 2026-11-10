# Data Analyst Job Market Analysis (SQL)

## Introduction
This project uses SQL to explore the data analyst job market: which jobs pay the most, which skills are most in demand, and which skills are worth learning first.

## Tools
- **PostgreSQL**: database
- **SQL**: querying and analysis
- **Visual Studio Code**: editor, with the SQLTools extension
- **Git and GitHub**: version control

## Dataset
The data comes from [source of your dataset] and holds job postings with titles, locations, salaries, and skills. It is organized in four tables:

| Table | Description |
|---|---|
| `job_postings_fact` | One row per job posting |
| `company_dim` | Company information |
| `skills_dim` | List of skills |
| `skills_job_dim` | Links each job to its skills |

## The Questions

| # | File | Question |
|---|---|---|
| 1 | [1_top_paying_jobs.sql](project_sql/1_top_paying_jobs.sql) | What are the top-paying data analyst jobs? |
| 2 | [2_top_paying_job_skills.sql](project_sql/2_top_paying_job_skills.sql) | What skills do those top-paying jobs require? |
| 3 | [3_top_demanded_skills.sql](project_sql/3_top_demanded_skills.sql) | What are the most in-demand skills? |
| 4 | [4_top_average_skills.sql](project_sql/4_top_average_skills.sql) | Which skills are linked to higher salaries? |
| 5 | [5_optimal_skills.sql](project_sql/5_optimal_skills.sql) | Which skills are both in demand and well paid? |

## Key Findings
- **Top-paying jobs:** [write what you found]
- **Skills for top-paying jobs:** [write what you found]
- **Most in-demand skills:** [write what you found]
- **Skills with the highest average salary:** [write what you found]
- **Best skills to learn:** [write what you found]

## What I Learned
- Joining multiple tables (`INNER JOIN`, `LEFT JOIN`)
- Aggregations with `GROUP BY`, `HAVING`, `COUNT`, and `AVG`
- Writing readable queries with CTEs and `CASE WHEN`
- Setting up PostgreSQL and loading CSV data

## How to Run
1. Install PostgreSQL and create a database.
2. Create the tables and load the CSV data.
3. Run the queries in the `project_sql` folder.

## Conclusion
[Two or three sentences on what the analysis shows and what you'd do next.]
