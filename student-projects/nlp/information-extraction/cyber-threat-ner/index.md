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

The student builds a named entity recognition system aligned with the STIX 2.1 standard, targeting entities such as malware, threat actors, and indicators of compromise. The main goal is to move from raw reports to structured data that can be used in downstream security systems.

---

## Data

The project uses a synthetic but structured cybersecurity corpus designed to reflect real CTI scenarios.

- Annotated CTI dataset created in Doccano (JSONL format)  
- Gazetteer lists derived from STIX 2.1 terminology and public IOC sources  
- Simulated inputs including security blogs, incident reports, and IOC feeds  

Dataset size:

- ~1,000 training examples  
- 200 validation examples  
- 200 test examples  

Entities:

- Indicator  
- Malware  
- Report  
- Threat-Actor  
- Tool  

One thing to keep in mind is that the data is synthetic. That makes it easier to control labeling, but it also leads to cleaner patterns than would appear in real-world CTI.

---

## Approach

The project compares two models.

Baseline:

- Fine-tuned `bert-base-cased` for token classification  
- Standard Hugging Face Trainer setup  
- No domain-specific features  

Hybrid model:

- Same BERT backbone  
- Gazetteer-based features added as token-level signals  
- Regex rules for structured entities such as IPs, domains, and hashes  
- Combined lexical and contextual signals during training  

In general, the idea is simple. Let the transformer handle context, and let domain knowledge handle structure.

---

## Tech Stack

- Hugging Face transformers and datasets  
- PyTorch (training backend)  
- spaCy (token alignment and preprocessing)  
- Doccano (annotation pipeline)  
- Google Colab with Tesla T4 GPU  

Note that the pipeline is fairly standard. The main difference is how domain knowledge is injected into the model.

---

## Evaluation

Evaluation is done using macro F1 on both clean and noisy datasets.

Clean dataset:

- Baseline BERT: 0.995 to 1.000 F1  
- Hybrid model: approximately 1.000 F1  

Noisy dataset:

- Baseline BERT: 0.648 F1  
- Hybrid model: 0.699 F1  

The gap on the noisy dataset is the key result.

---

## Results

On clean data, both models perform almost perfectly. That is expected given the controlled nature of the dataset.

On noisy data, the hybrid model shows a clear improvement. The gain is modest in absolute terms, but meaningful for harder entity types.

In particular:

- Structured entities benefit from regex features  
- Rare or domain-specific terms benefit from gazetteers  
- The transformer alone struggles more in these cases  

At that point, the value of combining approaches becomes clear.

---

## Takeaways

This project shows a useful pattern for domain-specific NLP work.

- Transformer models provide strong baseline performance  
- Domain knowledge still matters, especially in noisy settings  
- Hybrid systems can improve robustness without major architectural changes  

If extended with real CTI data, this approach would likely show a larger performance gap.

---
