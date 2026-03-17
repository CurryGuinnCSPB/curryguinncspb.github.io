---
title: "Social Media Misinformation Detection"
layout: single
permalink: /student-projects/nlp/text-classification/misinformation-detection/
excerpt: "Detects misinformation in social media posts."
image: /assets/images/student-projects/nlp/misinformation-detection/hero.jpg
toc: false
---

## Overview

This project focuses on detects misinformation in social media posts.

This project addresses the critical challenge of automatically detecting misinformation in social media posts and news headlines. Using the FakeNewsNet dataset comprising over 23,000 news headlines from GossipCop and PolitiFact sources, I developed a BERT-based classiﬁcation model to distinguish between real and fake news.

---

## Data and Modeling

The project uses X as its primary dataset.

The core system is built around BERT, RoBERTa, transformer. The model combines contextual language modeling with domain-specific signals so that structured entities are easier to detect.

The implementation uses transformers.

---

## Results

Reported evaluation includes F1: **0.90**, F1: **0.69**, F1: **0.6944**, and F1: **0.6330**. The results suggest that the system is effective on the target task and provides a useful baseline for future work.

---

## Why This Matters

Classification projects like this matter because they turn large collections of text into signals that can actually be used. That can support moderation, decision-making, or domain analysis depending on the setting.
