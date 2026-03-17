---
title: "Emotional Tone After Wins and Losses"
layout: single
permalink: /student-projects/nlp/text-classification/emotional-tone-analysis/
excerpt: "Analyzes emotional tone shifts in sports and political commentary."
image: /assets/images/student-projects/nlp/emotional-tone-analysis/hero.jpg
toc: false
---

## Overview

This project focuses on analyzes emotional tone shifts in sports and political commentary.

​ This project examines how emotional language shifts after wins and losses in the two very highly public domains of politics and sports. While both of these fields involve high stakes, pressurized situations, and public facing communication, they do differ in tone and expression and the purpose of their communications.

---

## Data and Modeling

The project draws on GoEmotions, Twitter, X.

The core system is built around BERT, TF-IDF, transformer. The pipeline separates retrieval from generation so the system can first identify useful context and then produce an answer from that material.

The implementation uses transformers.

---

## Results

The project reports qualitative or comparative results rather than a single headline metric. The results show a clear improvement over the comparison baseline or over simpler alternatives.

---

## Why This Matters

Classification projects like this matter because they turn large collections of text into signals that can actually be used. That can support moderation, decision-making, or domain analysis depending on the setting.
