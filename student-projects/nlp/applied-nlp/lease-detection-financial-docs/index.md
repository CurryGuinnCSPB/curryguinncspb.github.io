---
title: "Automated Lease Detection in Financial Documents"
layout: single
permalink: /student-projects/nlp/applied-nlp/lease-detection-financial-docs/
excerpt: "Extracts lease obligations from accounting documents."
image: /assets/images/student-projects/nlp/lease-detection-financial-docs/hero.jpg
toc: false
---

## Overview

This project focuses on extracts lease obligations from accounting documents.

Under the accounting standard ASC 842, companies are required to capitalize leases on their balance sheets. This has turned a routine compliance task into a massive data processing challenge, requiring accountants to manually review thousands of contracts to distinguish true leases from service agreements.

---

## Data and Approach

The project uses X as its primary dataset.

The core system is built around BERT, TF-IDF, Logistic Regression, transformer. The pipeline separates retrieval from generation so the system can first identify useful context and then produce an answer from that material.

The implementation centers on pretrained models and standard Python NLP tooling.

---

## Results

The project reports qualitative or comparative results rather than a single headline metric. The results point to a workable solution for the target task and a clear path for refinement.

---

## Why This Matters

This project shows how NLP techniques can be adapted to a concrete problem rather than used only as benchmarks. That practical step is what makes the work especially useful on a public-facing portfolio page.
