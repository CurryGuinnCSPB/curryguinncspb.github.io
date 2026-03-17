---
title: "Stock Prediction from News Sentiment"
layout: single
permalink: /student-projects/nlp/applied-nlp/stock-sentiment-prediction/
excerpt: "Predicts stock trends using sentiment from news data."
image: /assets/images/student-projects/nlp/stock-sentiment-prediction/hero.jpg
toc: false
---

## Overview

This project focuses on predicts stock trends using sentiment from news data.

This project asks a simple question: does news sentiment about Apple (AAPL) or Microsoft (MSFT) tell us anything useful about the stock’s same-day move from open to close? I compute headline-level sentiment with two widely used tools—VADER (a lexicon method) and FinBERT (a finance-tuned transformer)—then aggregate to daily features per ticker.

---

## Data and Approach

The project draws on Twitter, X.

The core system is built around BERT, Logistic Regression, RAG, transformer. The workflow emphasizes text preprocessing, feature representation, and supervised prediction of the target labels.

The implementation uses NLTK.

---

## Results

The project reports qualitative or comparative results rather than a single headline metric. The results show a clear improvement over the comparison baseline or over simpler alternatives.

---

## Why This Matters

This project shows how NLP techniques can be adapted to a concrete problem rather than used only as benchmarks. That practical step is what makes the work especially useful on a public-facing portfolio page.
