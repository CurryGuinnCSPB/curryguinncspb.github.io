---
title: "Cyber Threat Intelligence NER (STIX 2.1)"
layout: single
permalink: /student-projects/nlp/information-extraction/cyber-threat-ner/
excerpt: "A hybrid transformer-based system for extracting STIX 2.1 entities from cybersecurity text."
image: /assets/images/student-projects/nlp/cyber-threat-ner/hero.jpg
toc: false
---

## Overview

This project focuses on extracting structured threat intelligence from unstructured cybersecurity text.

The system is designed around the STIX 2.1 standard and targets entities such as malware, threat actors, tools, and indicators of compromise. The goal is to move from narrative security reports to structured representations that can support downstream analysis and automated threat detection.

---

## Data and Approach

The dataset consists of a structured cybersecurity corpus created to reflect common CTI scenarios. The data was annotated using Doccano and includes simulated inputs such as incident reports, security blogs, and IOC feeds. Gazetteer lists derived from STIX terminology and public indicator sources were also incorporated.

The dataset includes approximately:
- 1,000 training examples  
- 200 validation examples  
- 200 test examples  

The model targets five entity types: Indicator, Malware, Report, Threat-Actor, and Tool.

Two approaches are compared.

The baseline uses a standard fine-tuned `bert-base-cased` model for token classification. The second approach augments this model with domain-specific signals. Gazetteer features are added at the token level, and regular expressions are used to capture structured entities such as IP addresses, domains, and file hashes.

The resulting system combines contextual representations from the transformer with explicit domain knowledge, allowing it to better handle both linguistic variation and structured patterns.

---

## Results

Evaluation is performed using macro F1 on both clean and noisy datasets.

On the clean dataset, both models perform near perfectly:
- Baseline BERT: **0.995 to 1.000 F1**  
- Hybrid model: **~1.000 F1**

On the noisy dataset, the difference between the approaches becomes more apparent:
- Baseline BERT: **0.648 F1**  
- Hybrid model: **0.699 F1**

This represents an improvement of roughly five F1 points under more realistic conditions.

The gains are most noticeable for structured and domain-specific entities. Gazetteer features help with rare terminology, while regex patterns improve recognition of indicators such as IP addresses and hashes. The transformer model provides strong contextual understanding, and the additional signals improve robustness when the input becomes less predictable.

---

## Why This Matters

Cyber threat intelligence is inherently unstructured. Analysts often work with long-form reports, blog posts, and fragmented indicators that must be translated into structured formats before they can be used effectively.

This project shows how that translation can be partially automated. It also highlights an important pattern in applied NLP. Transformer models provide a strong foundation, but domain knowledge can still play a critical role, especially in specialized settings.

By combining learned representations with structured signals, the system improves performance in the conditions that matter most, where data is noisy, incomplete, and domain-specific.