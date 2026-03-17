---
title: "Cyber Threat Intelligence NER (STIX 2.1)"
layout: single
permalink: /student-projects/nlp/information-extraction/cyber-threat-ner/
excerpt: "A hybrid transformer-based system for extracting STIX 2.1 entities from cybersecurity text."
image: /assets/images/student-projects/nlp/cyber-threat-ner/hero.jpg
toc: false
---

## Abstract

This project develops a named entity recognition system for extracting structured cyber threat intelligence from unstructured text, aligned with the STIX 2.1 standard. The task focuses on identifying entities such as malware, threat actors, tools, reports, and indicators of compromise from sources including incident reports, security blogs, and IOC feeds. The dataset consists of a curated and annotated corpus created using Doccano, with approximately 1,000 training examples and 200 examples each for validation and testing. In addition to the annotated data, the system incorporates domain-specific resources, including gazetteer lists derived from STIX terminology and publicly available indicator sources, enabling the model to leverage both contextual and structured signals.

Two modeling approaches are evaluated. The baseline uses a fine-tuned `bert-base-cased` model for token classification, while the second approach augments this architecture with domain knowledge through gazetteer-based features and regular expressions targeting structured entities such as IP addresses, domains, and file hashes. Performance is evaluated using macro F1 on both clean and noisy datasets. On clean data, both models achieve near-perfect performance, with the baseline ranging from 0.995 to 1.000 F1 and the hybrid model reaching approximately 1.000 F1. On noisier data, the hybrid approach shows a consistent improvement, increasing F1 from 0.648 to 0.699. These results highlight the role of domain-specific signals in improving robustness under realistic conditions and demonstrate a broader pattern in applied NLP: while transformer models provide strong baseline performance, incorporating structured domain knowledge can meaningfully improve performance in specialized settings.