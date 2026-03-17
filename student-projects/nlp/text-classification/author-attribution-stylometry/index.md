---
title: "Author Attribution with Stylometry"
layout: single
permalink: /student-projects/nlp/text-classification/author-attribution-stylometry/
excerpt: "Uses stylometric features to attribute authorship."
image: /assets/images/student-projects/nlp/author-attribution-stylometry/hero.jpg
toc: false
---

## Overview

This project focuses on uses stylometric features to attribute authorship.

This project explores authorship attribution using two different methodologies: a traditional, feature-based approach grounded in stylometry and a modern transformer-based approach using deep contextual embeddings. I implemented both pipelines on literary texts from the NLTK Gutenberg corpus, segmented into 50-word chunks.

---

## Data and Modeling

The project draws on Project Gutenberg, Twitter, X.

The core system is built around BERT, SVM, Logistic Regression, Random Forest. The pipeline separates retrieval from generation so the system can first identify useful context and then produce an answer from that material.

The implementation uses Hugging Face, scikit-learn, NLTK.

---

## Results

The project reports qualitative or comparative results rather than a single headline metric. The results show a clear improvement over the comparison baseline or over simpler alternatives.

---

## Why This Matters

Classification projects like this matter because they turn large collections of text into signals that can actually be used. That can support moderation, decision-making, or domain analysis depending on the setting.
