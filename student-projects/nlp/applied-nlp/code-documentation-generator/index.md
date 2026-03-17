---
title: "Code Documentation Generator"
layout: single
permalink: /student-projects/nlp/applied-nlp/code-documentation-generator/
excerpt: "Automatically generates documentation from source code."
image: /assets/images/student-projects/nlp/code-documentation-generator/hero.jpg
toc: false
---

## Overview

This project focuses on automatically generates documentation from source code.

This project explores automated generation of code documentation for Python functions using transformer-based models. I implemented and evaluated CodeBERT for automatic docstring generation using the CodeSearchNet dataset, treating code documentation as a sequence-to-sequence translation task.

---

## Data and Approach

The project draws on X, CodeDocDataset.

The core system is built around BERT, RAG, transformer. The model combines contextual language modeling with domain-specific signals so that structured entities are easier to detect.

The implementation uses Hugging Face, transformers, ROUGE.

---

## Results

Reported evaluation includes Accuracy: **0.17**, and ROUGE-1: **0.24**. The results show a clear improvement over the comparison baseline or over simpler alternatives.

---

## Why This Matters

This project shows how NLP techniques can be adapted to a concrete problem rather than used only as benchmarks. That practical step is what makes the work especially useful on a public-facing portfolio page.
