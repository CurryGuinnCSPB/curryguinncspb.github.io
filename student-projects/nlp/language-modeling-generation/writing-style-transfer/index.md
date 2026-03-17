---
title: "Writing Style Transfer"
layout: single
permalink: /student-projects/nlp/language-modeling-generation/writing-style-transfer/
excerpt: "Transfers writing style between authors."
image: /assets/images/student-projects/nlp/writing-style-transfer/hero.jpg
toc: false
---

## Overview

This project focuses on transfers writing style between authors.

2 This project explored Text Style Transfer from neutral to stylized writing by fine-tuning GPT-2 Medium using open source Hugging Face transformers on Google Colab. The dataset consisted of 300 text chunks from Herman Melville's three most popular novels paired with corresponding neutralized texts generated using ChatGPT.

---

## Data and System Design

The project draws on Project Gutenberg, X.

The core system is built around T5, GPT-2, RAG, transformer. The workflow is designed to move from raw text to a structured or interpretable output with as little manual intervention as possible.

The implementation uses Hugging Face, transformers, ROUGE.

---

## Results

The project reports qualitative or comparative results rather than a single headline metric. The results suggest that the system is effective on the target task and provides a useful baseline for future work.

---

## Why This Matters

Generation projects are useful because they show how language models can move from pattern recognition to actual output creation. This project also makes clear that dataset design and prompting choices shape the final result.
