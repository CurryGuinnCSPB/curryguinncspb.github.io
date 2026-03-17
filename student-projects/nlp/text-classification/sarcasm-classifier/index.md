---
title: "Tweet Sarcasm Classifier"
layout: single
permalink: /student-projects/nlp/text-classification/sarcasm-classifier/
excerpt: "Machine learning model for sarcasm detection."
image: /assets/images/student-projects/nlp/sarcasm-classifier/hero.jpg
toc: false
---

## Overview

This project focuses on machine learning model for sarcasm detection.

Sarcasm detection is a challenging problem in natural language processing (NLP) due to its reliance on subtle linguistic cues, context, and tone. This project investigates sarcasm detection in short-form social media text using the TweetEval irony dataset.

---

## Data and Modeling

The project draws on SARC, TweetEval, Twitter.

The core system is built around BERT, RoBERTa, DistilBERT, TF-IDF. The pipeline separates retrieval from generation so the system can first identify useful context and then produce an answer from that material.

The implementation centers on pretrained models and standard Python NLP tooling.

---

## Results

Reported evaluation includes F1: **0.6454**, F1: **0.6705**, Accuracy: **0.6416**, and Accuracy: **0.6712**. The results point to a workable solution for the target task and a clear path for refinement.

---

## Why This Matters

Classification projects like this matter because they turn large collections of text into signals that can actually be used. That can support moderation, decision-making, or domain analysis depending on the setting.
