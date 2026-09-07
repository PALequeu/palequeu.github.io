---
title: "The GDN-CC Dataset: Automatic Corpus Clarification for AI-enhanced Democratic Citizen Consultations"
collection: publications
category: conferences
permalink: /publication/GDNCC
excerpt: "[Paper](https://aclanthology.org/2026.acl-long.1523/) - We introduce Corpus Clarification, a preprocessing framework of citizens consultation data which allow for ethical downstream analysis. We share a manually-annotated dataset based on the 2019 French consultation 'Grand Débat National', and a large automatically annotated dataset using SLMs finetuned for the task."
date: 2026-07-07
venue: 'ACL'
slidesurl: #'https://palequeu.github.io/files/slides1.pdf'
paperurl: 'https://palequeu.github.io/files/GDN-CC.pdf'
bibtexurl: 'https://palequeu.github.io/files/GDN-CC.bib'
citation: 'Pierre-Antoine Lequeu, Léo Labat, Laurène Cave, Gaël Lejeune, François Yvon, and Benjamin Piwowarski. 2026. The GDN-CC Dataset: Automatic Corpus Clarification for AI-enhanced Democratic Citizen Consultations. In Proceedings of the 64th Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers), pages 32976–33006, San Diego, California, United States. Association for Computational Linguistics.'
---
LLMs are ubiquitous in modern NLP, and while their applicability extends to texts produced for democratic activities such as online deliberations or large-scale citizen consultations, ethical questions have been raised for their usage as analysis tools. We continue this line of research with two main goals: (a) to develop resources that can help standardize citizen contributions in public forums at the pragmatic level, and make them easier to use in topic modeling and political analysis; (b) to study how well this standardization can reliably be performed by small, open-weights LLMs, i.e. models that can be run locally and transparently with limited resources. Accordingly, we introduce Corpus Clarification as a preprocessing framework for large-scale consultation data that transforms noisy, multi-topic contributions into structured, self-contained argumentative units ready for downstream analysis. We present GDN-CC, a manually-curated dataset of 1,231 contributions to the French Grand Débat National, comprising 2,285 argumentative units annotated for argumentative structure and manually clarified. We then show that finetuned Small Language Models match or outperform LLMs on reproducing these annotations, and measure their usability for an opinion clustering task. We finally release GDN-CC-large, an automatically annotated corpus of 240k contributions, the largest annotated democratic consultation dataset to date.
