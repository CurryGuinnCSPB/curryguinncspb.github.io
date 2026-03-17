---
title: "Taylor Swift Lyric Generator"
layout: single
permalink: /student-projects/nlp/language-modeling-generation/taylor-swift-lyrics-generator/
excerpt: "Generates song lyrics in the style of Taylor Swift."
image: /assets/images/student-projects/nlp/taylor-swift-lyrics-generator/hero.jpg
toc: false
---

## Overview

This project focuses on generates song lyrics in the style of Taylor Swift.

This study examined whether adding explicit song structure improves the quality of AI- generated lyrics in the style of Taylor Swift. Two Phi-3-mini models were ﬁne-tuned using a controlled design: one received only style keywords (control), and the other also received structure templates, such as Verse  Chorus  Bridge (treatment).

---

## Data and System Design

The project uses X as its primary dataset.

The core system is built around GPT-2, RAG, transformer. The model combines contextual language modeling with domain-specific signals so that structured entities are easier to detect.

The implementation uses ROUGE.

---

## Results

The project reports qualitative or comparative results rather than a single headline metric. The results show a clear improvement over the comparison baseline or over simpler alternatives.

---

## Why This Matters

Generation projects are useful because they show how language models can move from pattern recognition to actual output creation. This project also makes clear that dataset design and prompting choices shape the final result.
