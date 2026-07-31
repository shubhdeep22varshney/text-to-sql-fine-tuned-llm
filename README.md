# Text-to-SQL using Fine-Tuned LLM (Mistral-7B)

## Overview
This project focuses on converting natural language questions into SQL queries using a fine-tuned Large Language Model (LLM).

The Mistral-7B model is fine-tuned to generate SQL statements from user queries, enabling natural language interaction with databases.

## Model Details

- Base Model: mistralai/Mistral-7B-v0.1
- Fine-Tuned Model: Hugging Face Model
- Dataset: SPARC Text-to-SQL Dataset

## Objective

To build an AI-powered Text-to-SQL system that allows users to query databases using natural language instead of manually writing SQL queries.

## Technologies Used

- Python
- Hugging Face Transformers
- Mistral-7B
- Large Language Models (LLMs)
- Natural Language Processing (NLP)
- SQL

## Workflow

1. Collect and preprocess Text-to-SQL dataset.
2. Fine-tune Mistral-7B model.
3. Provide natural language input.
4. Generate corresponding SQL query.
5. Evaluate generated SQL output.

## Resources

Fine-Tuned Model:
https://huggingface.co/caffeic/text-to-sql-model

Training Notebook:
(Add Kaggle notebook link)

Testing Notebook:
https://colab.research.google.com/drive/18emVCSk5UzbQfCV9kf_nftpcLNBlyG6F?usp=sharing

Dataset:
https://astroweb.case.edu/SPARC/

## Evaluation

- Validation Loss: 0.127302
- Human evaluation performed on generated SQL queries.
