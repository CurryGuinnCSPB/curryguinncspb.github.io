---
title: "Stance Detection in News Text"
layout: single
permalink: /student-projects/nlp/text-classification/stance-detection-news/
excerpt: "Identifies stance and bias in news articles."
image: /assets/images/student-projects/nlp/stance-detection-news/hero.jpg
toc: false
---

## Overview

This project focuses on identifies stance and bias in news articles.

This project investigates stance detection in text using three diverse datasets: Internet Argument Corpus (IAC), Perspectrum, and Emergent. A traditional machine learning model, TF-IDF with logistic regression, is compared to a transformer-based model, RoBERTa-base, to classify text as supporting, critical, or neutral toward claims.

---

## Data and Modeling

The project draws on X, Macro F1 Scores Across Dataset.

The core system is built around BERT, RoBERTa, TF-IDF, Logistic Regression. The pipeline separates retrieval from generation so the system can first identify useful context and then produce an answer from that material.

The implementation uses Hugging Face, transformers.

---

## Results

The project reports qualitative or comparative results rather than a single headline metric. The results show a clear improvement over the comparison baseline or over simpler alternatives.

---

## Why This Matters

Classification projects like this matter because they turn large collections of text into signals that can actually be used. That can support moderation, decision-making, or domain analysis depending on the setting.
