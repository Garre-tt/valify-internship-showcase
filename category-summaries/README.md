# Category Summaries Project

## Overview

This project focuses on generating concise descriptions for each category in Valify's hospital spend analysis categorization tree. The goal is to create informative summaries for display on Valify's website, enhancing user understanding of each spend category.

## Key Features

- Utilizes SQL queries to gather relevant category information
- Implements a multi-step AI querying process using Claude 3 Haiku and Claude 3.5 Sonnet
- Generates comprehensive category summaries based on collected data and AI-generated insights

## Technologies Used

- Python
- AWS Bedrock
- Anthropic Claude LLM models (Haiku and Sonnet)
- SQL and PostgreSQL
- AWS boto3
- pandas

## Process

1. SQL queries extract initial category data based on category ID
2. Claude 3 Haiku is used to gather additional contextual information
3. All collected data is processed by Claude 3.5 Sonnet to generate the final summary

## Setup and Usage

Detailed instructions for setting up the virtual environment, installing dependencies, and running the script can be found in the project's [full README](./README.md).

## Key Learnings

- Advanced LLM prompting techniques
- Optimization of AI model selection for different tasks
- Efficient data handling with pandas and SQL
- Integration of multiple data sources for comprehensive summaries

## Challenges Overcome

- LLM inconsistency and accuracy issues
- Handling complex sets of categories
- Virtual environment configuration
- Balancing detail and conciseness in summaries

This project significantly enhanced my skills in AI-driven content generation, data processing, and software development practices.
