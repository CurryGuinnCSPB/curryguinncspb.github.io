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

The work explores two complementary directions. The first compares several fine-tuned transformer models. The second examines how a modern large language model performs on the same task under different evaluation conditions. The project concludes with a working Python application that allows users to query a database in natural language.

---

## Data and Approach

The initial experiments use WikiSQL, a large dataset of natural language questions paired with SQL queries and tables. A later phase moves to SQL-Create-Context, which combines data from WikiSQL and Spider and represents database schemas using `CREATE TABLE` statements.

Several pretrained models are fine-tuned, including T5-small, CodeT5-small, CodeT5-base, and BART-base. After this comparison, CodeT5-base is selected for further work. Claude 3.7 Sonnet is then added as a second approach to the same task.

The final system integrates both models into a Python application. A user provides a schema and a question, the system generates candidate SQL queries, and the user can execute the selected query against a database.

---

## Results

The comparison shows a consistent pattern across models and datasets. In the initial WikiSQL experiments, **CodeT5-base achieved an Exact Match score of approximately 0.67**, outperforming the smaller models and establishing a strong baseline for the next phase.

In the SQL-Create-Context evaluation, CodeT5-base again performed well and outperformed Claude 3.7 Sonnet on Exact Match, ROUGE-2, and BLEU. When Exact Match is relaxed to ignore formatting differences such as capitalization and punctuation, Claude’s performance improves substantially, narrowing the gap between the models.

---

## Why This Matters

Text-to-SQL is a practical application of NLP because it lowers the barrier to working with structured data. A user can ask a question in ordinary language and get back a real query.

One thing that stands out here is that the project does not stop at comparing models. It also builds the application layer, which makes the work easier to demonstrate and easier to understand.
