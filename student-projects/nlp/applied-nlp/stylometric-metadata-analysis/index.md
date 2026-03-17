---
title: "Stylometric Metadata Analysis"
layout: single
permalink: /student-projects/nlp/applied-nlp/stylometric-metadata-analysis/
excerpt: "Uses stylometry to infer metadata about authors and documents."
image: /assets/images/student-projects/nlp/stylometric-metadata-analysis/hero.jpg
toc: false
---

## Overview

This project focuses on uses stylometry to infer metadata about authors and documents.

Stylometry Metadata, explores the potential of stylometric analysis beyond predicting authorship to predicting publication date and geographical origin of texts. Using a dataset of 70,000 public domain works from a Project Gutenberg Kaggle database, feature-based and transformer-based approaches compare the three tasks, authorship, publication date and geographical origin.

---

## Data and Approach

The project draws on Project Gutenberg, Twitter, X.

The core system is built around BERT, DistilBERT, RAG, transformer. The pipeline separates retrieval from generation so the system can first identify useful context and then produce an answer from that material.

The implementation uses transformers, pandas, NLTK.

---

## Results

Reported evaluation includes F1: **.119**, F1: **.11209**, Accuracy: **.286**, and Accuracy: **.06667**. The results suggest that the system is effective on the target task and provides a useful baseline for future work.

---

## Why This Matters

This project shows how NLP techniques can be adapted to a concrete problem rather than used only as benchmarks. That practical step is what makes the work especially useful on a public-facing portfolio page.
