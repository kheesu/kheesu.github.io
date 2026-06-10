---
permalink: /research/
title: "Research Vision"
author_profile: true
---

Modern foundation models learn rich representations of language, culture, and visual information, yet we still have limited understanding of what these representations encode and how they should be evaluated. My research asks: *what do neural representations actually capture about language, culture, and meaning — and how can we evaluate and improve them?*

## Evaluation

Benchmarks can be gamed, saturated, or misaligned with the competencies they claim to measure. I am interested in building evaluation frameworks that are sensitive to the cultural, linguistic, and semantic dimensions that standard leaderboards obscure.

**Cultural Evaluation of LLMs** *(first author; under review at ACL Rolling Review, May 2026 cycle)*  
I led the construction of the Korean subset of a multilingual cultural-bias benchmark and evaluated current LLMs under zero-shot, chain-of-thought, and supervised fine-tuning conditions. The benchmark probes culturally situated knowledge rather than surface-level pattern matching, extending prior Japanese-only work to a multilingual setting.

**Bias-a-Thon 2025 (3rd place, Track 1)**  
Identified and mitigated demographic biases in widely used LLMs at a hackathon hosted by SKKU's Center for Multimedia Intelligence (awarded by the Dean of the College of Computing and Informatics).

## Semantic Representations

Language is not static — words change meaning across time, domains, and communities. Contextual embeddings offer a powerful lens for studying this change, but the relationship between geometric shifts in representation space and human-interpretable meaning is not well understood.

**Semantic Shift Detection** *(ongoing, Komachi Lab)*  
Working on methods for measuring semantic change through contextual embeddings, studying how lexical meaning evolves across domains and languages.

## Multimodal Systems

Vision-language models are increasingly capable, yet what linguistic structure their visual encoders actually learn remains opaque. I analyze multimodal representations to understand what syntactic and semantic information survives the visual encoding process.

**Linguistic Structure in Vision-Language Embeddings** *(ongoing)*  
Probing vision-language models to understand what syntactic and semantic information is retained in image encoders trained jointly with text.

## Other Work

**[Hi-DARTS: Hierarchical Dynamically Adapting Reinforcement Trading System](https://arxiv.org/abs/2509.12048)** *(co-author; ICTC 2025)*  
A hierarchical multi-agent RL framework where a meta-agent monitors market volatility and activates frequency-specialized sub-agents. Achieved 25.17% cumulative return (Sharpe ratio 0.75) in backtesting against buy-and-hold baselines on Apple stock (Jan–May 2025).

---

Across these threads, my goal is to contribute evaluation tools and empirical findings that make AI systems more linguistically faithful, culturally aware, and interpretable.
