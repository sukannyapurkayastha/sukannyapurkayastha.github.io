---
title: "Romanization-based Large-scale Adaptation of Multilingual Language Models"
authors:
  - Sukannya Purkayastha
  - Sebastian Ruder
  - Jonas Pfeiffer
  - Iryna Gurevych
  - Ivan Vulić
date: "2023-12-01T00:00:00Z"
publishDate: "2023-12-01T00:00:00Z"
publication_types: ["inproceedings"]
publication: "Findings of the Association for Computational Linguistics: EMNLP 2023"
publication_short: "Findings ACL: EMNLP 2023"
pages: "7996--8005"
abstract: |
  Large multilingual pretrained language models (mPLMs) have become the de facto state of the art for cross-lingual transfer in NLP. However, their large-scale deployment to many languages, besides pretraining data scarcity, is also hindered by the increase in vocabulary size and limitations in their parameter budget. In order to boost the capacity of mPLMs to deal with low-resource and unseen languages, we explore the potential of leveraging transliteration on a massive scale. In particular, we explore the UROMAN transliteration tool, which provides mappings from UTF-8 to Latin characters for all the writing systems, enabling inexpensive romanization for virtually any language. We first focus on establishing how UROMAN compares against other language-specific and manually curated transliterators for adapting multilingual PLMs. We then study and compare a plethora of data- and parameter-efficient strategies for adapting the mPLMs to romanized and non-romanized corpora of 14 diverse low-resource languages. Our results reveal that UROMAN-based transliteration can offer strong performance for many languages, with particular gains achieved in the most challenging setups: on languages with unseen scripts and with limited training data without any vocabulary augmentation. Further analyses reveal that an improved tokenizer based on romanized data can even outperform non-transliteration-based methods in the majority of languages.
summary: "Romanization-based Large-scale Adaptation of Multilingual Language Models — Findings ACL: EMNLP 2023."
tags:
  - Multilingual
  - Romanization
  - Adaptation
featured: true
links:
  - type: proceedings
    url: "https://aclanthology.org/2023.findings-emnlp.538/"
  - type: doi
    url: "https://doi.org/10.18653/v1/2023.findings-emnlp.538"
---

This page contains metadata and links for the EMNLP 2023 Findings paper on romanization-based adaptation of multilingual PLMs.

## BibTeX

```bibtex
@inproceedings{purkayastha-etal-2023-romanization,
    title = "{R}omanization-based Large-scale Adaptation of Multilingual Language Models",
    author = "Purkayastha, Sukannya  and
      Ruder, Sebastian  and
      Pfeiffer, Jonas  and
      Gurevych, Iryna  and
      Vuli{\'c}, Ivan",
    editor = "Bouamor, Houda  and
      Pino, Juan  and
      Bali, Kalika",
    booktitle = "Findings of the Association for Computational Linguistics: EMNLP 2023",
    month = dec,
    year = "2023",
    address = "Singapore",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2023.findings-emnlp.538/",
    doi = "10.18653/v1/2023.findings-emnlp.538",
    pages = "7996--8005",
    abstract = "Large multilingual pretrained language models (mPLMs) have become the de facto state of the art for cross-lingual transfer in NLP. However, their large-scale deployment to many languages, besides pretraining data scarcity, is also hindered by the increase in vocabulary size and limitations in their parameter budget. In order to boost the capacity of mPLMs to deal with low-resource and unseen languages, we explore the potential of leveraging transliteration on a massive scale. In particular, we explore the UROMAN transliteration tool, which provides mappings from UTF-8 to Latin characters for all the writing systems, enabling inexpensive romanization for virtually any language. We first focus on establishing how UROMAN compares against other language-specific and manually curated transliterators for adapting multilingual PLMs. We then study and compare a plethora of data- and parameter-efficient strategies for adapting the mPLMs to romanized and non-romanized corpora of 14 diverse low-resource languages. Our results reveal that UROMAN-based transliteration can offer strong performance for many languages, with particular gains achieved in the most challenging setups: on languages with unseen scripts and with limited training data without any vocabulary augmentation. Further analyses reveal that an improved tokenizer based on romanized data can even outperform non-transliteration-based methods in the majority of languages."
}
```
