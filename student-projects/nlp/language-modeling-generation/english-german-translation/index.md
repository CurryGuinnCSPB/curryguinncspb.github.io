---
title: "English-German Machine Translation"
layout: single
permalink: /student-projects/nlp/language-modeling-generation/english-german-translation/
excerpt: "Neural machine translation between English and German."
image: /assets/images/student-projects/nlp/english-german-translation/hero.jpg
toc: false
---

## Overview

This project focuses on neural machine translation between English and German.

This project created four models, two basic and two custom, to help facilitate the translation of sentences from English to German. A custom, extremely simplified tokenizer was made to tokenize sentences and words to aid in the translations as the planned tokenizer (spaCy) was a little too complex and heavyweight for the goals of the project tokenizer.

---

## Data and System Design

The project uses X as its primary dataset.

The core system is built around spaCy, RAG. The workflow is designed to move from raw text to a structured or interpretable output with as little manual intervention as possible.

The implementation uses spaCy, pandas, NLTK.

---

## Results

The project reports qualitative or comparative results rather than a single headline metric. The results show a clear improvement over the comparison baseline or over simpler alternatives.

---

## Why This Matters

Generation projects are useful because they show how language models can move from pattern recognition to actual output creation. This project also makes clear that dataset design and prompting choices shape the final result.
