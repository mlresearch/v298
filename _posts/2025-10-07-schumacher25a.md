---
title: 'Rare Disease Differential Diagnosis with Large Language Models at Scale: From
  Abdominal Actinomycosis to Wilson’s Disease'
abstract: Large language models (LLMs) have demonstrated impressive capabilities in
  disease diagnosis. However, their effectiveness in identifying rarer diseases, which
  are inherently more challenging to diagnose, remains an open question. Rare disease
  performance is critical with the increasing use of LLMs in healthcare settings.  This
  is especially true if a primary care physician needs to make a rarer prognosis from
  only a patient conversation so that they can take the appropriate next step. To
  that end, several clinical decision support systems are designed to support providers
  in rare disease identification. Yet their utility is limited due to their lack of
  knowledge of common disorders and difficulty of use.   In this paper, we propose
  RareScale to combine the knowledge LLMs with expert systems.  We use jointly use
  an expert system and LLM to simulate rare disease chats.  This data is used to train
  a rare disease candidate predictor model.  Candidates from this smaller model are
  then used as additional inputs to black-box LLM to make the final differential diagnosis.
  Thus, RareScale allows for a balance between rare and common diagnoses.  We present
  results on over 575 rare diseases, beginning with Abdominal Actinomycosis and ending
  with Wilson’s Disease.  Our approach significantly improves the baseline performance
  of black-box LLMs by over 17% in Top-5 accuracy. We also find that our candidate
  generation performance is high (e.g. 88.8% on gpt-4o generated chats).
booktitle: Machine Learning for Healthcare 2025
year: '2025'
url: https://openreview.net/forum?id=rI2HzjtxXx
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: schumacher25a
month: 0
tex_title: 'Rare Disease Differential Diagnosis with Large Language Models at Scale:
  From Abdominal Actinomycosis to Wilson’s Disease'
cycles: false
bibtex_author: Schumacher, Elliot and Naik, Dhruv and Kannan, Anitha
author:
- given: Elliot
  family: Schumacher
- given: Dhruv
  family: Naik
- given: Anitha
  family: Kannan
date: 2025-10-07
address:
container-title: Proceedings of the 10th Machine Learning for Healthcare Conference
volume: '298'
genre: inproceedings
issued:
  date-parts:
  - 2025
  - 10
  - 7
pdf: https://raw.githubusercontent.com/mlresearch/v298/main/assets/schumacher25a/schumacher25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
