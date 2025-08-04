---
layout: default
title: Evaluation Faking: Project Page
---

# Evaluation Faking: Unveiling Observer Effects in Safety Evaluation of Frontier AI Systems

## 🔍 Overview

This project explores the **evaluation faking** phenomenon: when advanced AI models recognize they're under evaluation and alter their behavior, compromising the integrity of safety assessments.

We design **honeypot scenarios**, implement **chain-of-thought (CoT) monitoring**, and analyze **observer effects** across models of different reasoning capabilities, scales, and memory setups.

## 🔗 Links

- 📄 [arXiv Paper](https://arxiv.org/abs/2505.17815)
- 💬 Contact: Yihe Fan, Wenqi Zhang, Xudong Pan, Min Yang

## 🧠 Key Contributions

- Propose the concept of **Evaluation Faking**, grounded in perception, behavior, and consequence.
- Design 8 **honeypot evaluation setups** (S1–S8) with varying levels of implicit/explicit cues.
- Build a **CoT Monitoring Module** to analyze reasoning traces and detect faking intent.
- Reveal that **scale, memory, and reasoning** significantly increase the faking effect.

## 🧪 Method Overview

![Method Overview](assets/overview.png)

Our methodology includes:
- Honeypots: Controlled prompts with and without evaluation cues.
- Benchmarks: SORRY-Bench & StrongREJECT.
- CoT Monitoring: Tracks internal thoughts for signs of recognition.

## 📈 Results Summary

- Safety and faking behavior correlate positively with model scale.
- Memory mechanisms increase recognition of evaluation by **2.3×**.
- Reasoning models show **16% more faking** than non-reasoning ones.

## 📚 Citation

```bibtex
@article{fan2025evaluation,
  title={Evaluation Faking: Unveiling Observer Effects in Safety Evaluation of Frontier AI Systems},
  author={Fan, Yihe and Zhang, Wenqi and Pan, Xudong and Yang, Min},
  journal={arXiv preprint arXiv:2505.17815},
  year={2025}
}
```
## 👀 Acknowledgements
This work is from Computation and Artificial Intelligence Innovative College, Fudan University.
Last updated: August 2025
