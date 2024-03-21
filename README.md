
# Gemini Vs ChatGPT SQL Analysis

## Description
This project involves SQL analysis comparing the benchmark scores of two AI models: Gemini Ultra and GPT-4 across various capabilities. The database includes information on models, capabilities, and benchmark scores for different tasks. This README provides an overview of the project, the SQL schema, questions addressed, and how to use the provided SQL queries to gain insights from the dataset.

## SQL Schema

The project's SQL schema consists of three tables:

- **Models**: Contains information about different AI models.
- **Capabilities**: Stores details of various capabilities evaluated in the benchmarks.
- **Benchmarks**: Records benchmark scores for different models and capabilities.

## Questions Addressed

1. What are the average scores for each capability on both the Gemini Ultra and GPT-4 models?
2. Which benchmarks does Gemini Ultra outperform GPT-4 in terms of scores?
3. What are the highest scores achieved by Gemini Ultra and GPT-4 for each benchmark in the Image capability?
4. Calculate the percentage improvement of Gemini Ultra over GPT-4 for each benchmark.
5. Retrieve the benchmarks where both models scored above the average for their respective models.
6. Which benchmarks show that Gemini Ultra is expected to outperform GPT-4 based on the next score?
7. Classify benchmarks into performance categories based on score ranges.
8. Retrieve the rankings for each capability based on Gemini Ultra scores.
9. Convert the Capability and Benchmark names to uppercase.
10. Provide the benchmarks along with their descriptions in a concatenated format.

## Usage
To utilize the provided SQL queries and analyze the Gemini Vs ChatGPT database, follow these steps:

1. Set up a SQL environment with a database management system (DBMS) like MySQL, PostgreSQL, or SQLite.
2. Create the necessary tables (`Models`, `Capabilities`, `Benchmarks`) using the provided SQL schema.
3. Insert data into the tables using the provided INSERT statements.
4. Execute the SQL queries corresponding to the questions of interest in your SQL environment.
5. Analyze the query results to gain insights into the benchmark scores and model performances.

---

Feel free to customize the README further to include any additional details or instructions specific to your project!
