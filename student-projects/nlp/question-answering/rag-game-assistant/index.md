---
title: "Retrieval-Augmented Game Assistant"
layout: single
permalink: /student-projects/nlp/question-answering/rag-game-assistant/
excerpt: "Builds a retrieval-augmented assistant for board game instructions."
image: /assets/images/student-projects/nlp/rag-game-assistant/hero.jpg
toc: false
---

## Overview

This project focuses on builds a retrieval-augmented assistant for board game instructions.

In this project, I implement a basic RAG system for the board game Panzer Leader. I processed a PDF of the rulebook to extract each rule.

---

## Data and Approach

The project uses X as its primary dataset.

The core system is built around Claude, RAG. The pipeline separates retrieval from generation so the system can first identify useful context and then produce an answer from that material.

The implementation centers on pretrained models and standard Python NLP tooling.

---

## Results

The project reports qualitative or comparative results rather than a single headline metric. The results show a clear improvement over the comparison baseline or over simpler alternatives.

---

## Why This Matters

Question answering remains one of the most direct ways people interact with NLP systems. This project shows how retrieval and generation can be combined to return focused answers instead of a list of documents.
