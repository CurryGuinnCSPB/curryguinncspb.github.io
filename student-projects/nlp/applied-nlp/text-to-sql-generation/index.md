---
title: "Text-to-SQL with Transformer Models and a Modern LLM"
layout: single
permalink: /student-projects/nlp/applied-nlp/text-to-sql-generation/
excerpt: "A Text-to-SQL system comparing fine-tuned transformer models with a modern LLM, with a working application for querying databases in natural language."
image: /assets/images/student-projects/nlp/text-to-sql-generation/hero.jpg
toc: false
---

## Overview

This project focuses on the Text-to-SQL task, translating natural language questions into SQL queries that can be executed against a database.

The work explores two complementary directions. The first is model-centric, comparing several fine-tuned transformer models. The second looks at how a modern large language model performs on the same task under different evaluation conditions. The project concludes with a working Python application that allows users to query a database in natural language.

---

## Data and Approach

The project uses two datasets at different stages.

The initial experiments use **WikiSQL**, a large dataset of over 80,000 natural language questions paired with SQL queries and tables. This phase focuses on model selection and uses an 80/20 split for training and evaluation. Prompts are standardized with a “Translate to SQL:” prefix before tokenization.

The later stage moves to **SQL-Create-Context**, which combines data from WikiSQL and Spider and represents database schemas using `CREATE TABLE` statements. This allows the model to condition directly on schema information during generation.

Several pretrained models are fine-tuned, including T5-small, CodeT5-small, CodeT5-base, and BART-base. After this comparison, CodeT5-base is selected for further work. In parallel, Claude 3.7 Sonnet is evaluated as a second approach to the same task.

The final system integrates both models into a Python application. A user provides a schema and a question, the system generates candidate SQL queries, and the user can execute the selected query against a database.

---

## Results

The comparison shows a consistent pattern across models and datasets. In the initial WikiSQL experiments, **CodeT5-base achieved an Exact Match score of approximately 0.67**, outperforming the smaller models and establishing a strong baseline for the next phase.

In the SQL-Create-Context evaluation, CodeT5-base again performed well and outperformed Claude 3.7 Sonnet on Exact Match, ROUGE-2, and BLEU. At the same time, the results highlight an important nuance. When Exact Match is relaxed to ignore formatting differences such as capitalization and punctuation, Claude’s performance improves substantially, narrowing the gap between the models.

This distinction is useful. Some of the performance difference reflects true query accuracy, while some reflects surface-level formatting choices. The project captures both perspectives and shows how evaluation criteria can influence conclusions.

The final system demonstrates these capabilities in a working interface, where natural language questions are translated into executable SQL queries and run against a database.

---

## Why This Matters

Text-to-SQL is a practical and increasingly important application of NLP. It allows users to interact with structured data using natural language rather than formal query languages.

This project shows how that capability can be built using both fine-tuned transformer models and modern LLMs. It also highlights the importance of schema-aware inputs, careful evaluation, and system integration beyond the model itself.

The result is not just a comparison of models, but a usable system that connects natural language understanding with real data access.
