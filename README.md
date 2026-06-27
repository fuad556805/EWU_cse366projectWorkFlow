## Project Title: Natural Language to SQL Query Generation System
(Compositional Learning).

## Project Objective

The goal of this project is to build a system that can convert simple English questions into SQL
queries. Many users do not know SQL, so it is difficult for them to get information from a
database. This system will allow users to ask questions in natural language and automatically
generate SQL queries.

Example:

## Question: "Show all CSE students" SQL Query: SELECT * FROM students WHERE
department='CSE';

The project is based on Compositional Learning, where a question is broken into smaller parts
before generating the final query.

## Existing Works

Systems such as Seq2SQL, SQLNet, and RAT-SQL perform well in text-to-SQL tasks but
require large datasets and high computational resources. This project uses a simpler and more
interpretable approach based on CSE366 concepts like HMM, Naive Bayes, MLP, and Intelligent
Agents, making it suitable for educational use.

## Why You Choose the Project

I chose this project because I am working on **[AutoAnalyst AI](https://autoanalyst-ai.onrender.com/)**, which analyzes datasets but cannot
understand natural language queries. This project will help solve that by converting user
questions into SQL queries automatically. It will also improve my knowledge of Artificial
Intelligence, Natural Language Processing, and database systems.

## References

1. Zhong et al. (2017), Seq2SQL.
2. Xu et al. (2017), SQLNet.
3. Wang et al. (2020), RAT-SQL.
4. Yu et al. (2018), Spider Dataset.
5. Raffel et al. (2020), T5 Transformer.
