---
title: "Give it Space! Explicit Disentangling of Positional and Semantic Representations in Encoders"
collection: publications
category: conferences
permalink: /publication/give_it_space
excerpt: "[Preprint](https://arxiv.org/abs/2605.30022) -  explored how encoder-based models use absolute positional (AP) and relative positional (RP) information by explicitly disentangling positional and semantic representations. We find that the learned AP representations are low dimensional and used to encode document structure, while RP information is used as complementary to semantic matching."
date: 2026-10-24
venue: 'EMNLP'
slidesurl: #'https://palequeu.github.io/files/slides1.pdf'
paperurl: 'https://palequeu.github.io/files/give_it_space.pdf'
bibtexurl: # 'https://palequeu.github.io/files/GDN-CC.bib'
citation: 'Lequeu, P. A., Barboule, C., & Piwowarski, B. (2026). Give it Space! Explicit Disentangling of Positional and Semantic Representations in Encoders. arXiv preprint arXiv:2605.30022.'
---
Positional encoding (PE) underpins how permutation-invariant Transformers represent sequence order, yet how positional information is processed and stored remains poorly understood. Modern PE methods such as RoPE still struggle on tasks such as long-context understanding or retrieval (Chen et al., 2025). Hence, a better understanding of the internal positional mechanism could help design better PE. Building on evidence that positional and semantic signals occupy nearly orthogonal subspaces in trained Transformers, we modify an encoder Transformer to process three explicitly disentangled streams: semantic, absolute positional (AP) and relative positional (RP), and confine the masked-language-modeling (MLM) objective to the semantic stream. This decoupling enables a clean mechanistic study and yields three take-aways. (1) The isolated AP subspace spontaneously collapses into a low-frequency two-dimensional manifold that captures the structure of the document; (2) Attention heads specialize into structure and semantic-oriented groups, with RP exclusively supporting the latter; (3) Standard positional encodings do not robustly retain macroscopic structure: RoPE and RP only weakly encode it, and entangled AP loses it in the final layers under MLM pressure. The disentangled approach preserves positional encoding, which improves linguistic representation on 49 of the 65 linguistic phenomena of the Flash-Holmes probing benchmark.
