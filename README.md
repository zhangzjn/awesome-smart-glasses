<div align="center">
  <h1 style="display: inline-flex; align-items: center;">
    <img src="assets/imgs/repo-logo.png" alt="Smart Glasses Survey Logo" width="60">
    From Seeing to Acting: Smart Glasses as First-Person Intelligence Platforms
  </h1>
</div>

<p align="center">
  <a href="https://github.com/sindresorhus/awesome"><img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" alt="Awesome list badge"></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="MIT License"></a>
  <a href="https://arxiv.org/abs/2608.24877"><img src="https://img.shields.io/badge/arXiv-Paper-b31b1b.svg?logo=arXiv" alt="arXiv"></a>
  <a href="https://huggingface.co/papers/2608.24877"><img src="https://img.shields.io/badge/Hugging_Face-Paper-292929.svg?logo=huggingface" alt="Hugging Face"></a>
  <a href="#-contributing"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs welcome"></a>
  <a href="assets/imgs/wechat-group.jpg"><img src="https://img.shields.io/badge/Group-WeChat-07c160?logo=wechat&logoColor=white" alt="WeChat Group"></a>
</p>

<p align="center">
  <a href="https://zhangzjn.github.io/">Jiangning Zhang</a> <sup>1,*,<a href="mailto:186368@zju.edu.cn">✉</a></sup>&nbsp;,&nbsp;
  <a href="">Haojun Chen</a> <sup>1,*</sup>&nbsp;,&nbsp;
  <a href="https://person.zju.edu.cn/yongliu">Yong Liu</a> <sup>1</sup>
</p>

<p align="center">
    <sup>1</sup>Zhejiang University, APRIL Lab
</p>

This repository accompanies our survey **From Seeing to Acting: Smart Glasses as First-Person Intelligence Platforms** and maintains a structured collection of smart-glasses products/platforms, foundational capabilities, and application scenarios, which will be continuously updated.For more details, kindly refer to our [paper](https://arxiv.org/abs/2608.24877) 🚀

💬 Researchers and industry practitioners are welcome to join our [WeChat group](assets/imgs/wechat-group.jpg); we look forward to exchanging ideas and collaborating with you.

<p align="center">
  <img src="assets/imgs/survey-pipeline.png" alt="Survey Pipeline" width="100%">
</p>

## 📰 News

<!-- News will be updated here. -->
- **2026-08-26**: We release our initial-version survey: [From Seeing to Acting: Smart Glasses as First-Person Intelligence Platforms](https://arxiv.org/abs/2608.24877).

## Table of Contents

- [🎯 Contributions](#contributions)
- [👓 Representative Smart-Glasses Products/Platforms](#representative-smart-glasses-productsplatforms)
- [📏 Foundational Capabilities for Smart Glasses](#foundational-capabilities-for-smart-glasses)
- [🌍 Application Scenes for Smart Glasses](#application-scenes-for-smart-glasses)
- [📄 Citation](#-citation)
- [🤝 Contributing](#-contributing)
- [🔗 Related Resources & Links](#-related-resources--links)
- [🤗 Acknowledgments](#acknowledgments)

## 🎯 Contributions

<details>
<summary><strong>1️⃣ A formal and hardware-grounded problem definition.</strong></summary>

We define smart glasses through a first-person observation stream, a closed-loop mapping from observation and intent to feedback, persistent state, and optional action, and a constrained utility objective that makes latency, energy, thermals, privacy, and social cost explicit. We further consolidate heterogeneous devices into eight verifiable hardware capability axes and route-aware product profiles, converting marketing categories into evidence-bearing experimental substrates.

</details>

<details>
<summary><strong>2️⃣ A compositional capability framework with explicit evidential boundaries.</strong></summary>

We synthesize seven interdependent capabilities: first-person perception, multimodal context, persistent spatial state, auditable personal memory, situated agentic action, embodied data interfaces, and cross-cutting deployment constraints. Building upon these building blocks, we present an L0-L5 framework that covers capture, reactive perception, contextual assistance, persistent state, governed action, and embodied coupling. The framework treats levels as task- and evidence-conditioned claims, distinguishes prerequisites from demonstrated capability, and makes clear that L5 crosses the embodiment boundary rather than simply extending the wearer-facing L0-L4 axis.

</details>

<details>
<summary><strong>3️⃣ An application-centered evidence map.</strong></summary>

We reorganize the literature into nine application scenes and connect each scene to its required capability loop, representative datasets and benchmarks, research systems, product entry points, affected stakeholders, failure consequences, and missing validation evidence. This structure separates transferable component evidence from direct smart-glasses evidence and clarifies why identical model functions require different thresholds in daily assistance, accessibility, industry, healthcare, education, mobility, social collaboration, spatial intelligence, and embodied intelligence.

</details>

<details>
<summary><strong>4️⃣ A deployment and evaluation blueprint.</strong></summary>

We formulate nine coupled design dimensions covering hardware, runtime, perception and inference, memory, feedback, external action, reliability, governance, and reproducibility. On this basis, we provide a claim-conditioned evaluation protocol, a deployment checklist, and an iterative evidence ladder that connects documentation, laboratory measurement, benchmark testing, device-stream replay, fault injection, end-to-end studies, longitudinal deployment, and privacy or security audit. We finally derive eight open challenges and six roadmap directions for building trustworthy first-person embodied-intelligence systems.

</details>

## Representative Smart-Glasses Products/Platforms

<p align="center">
  <img src="assets/imgs/products-timeline.png" alt="Survey Pipeline" width="100%">
</p>

<details>
<summary><strong>Figure: Hardware stack and hardware-based capability-axis consolidation. </strong></summary>

<p align="center">
  <img src="assets/imgs/hardware-capability-axes.png" alt="Survey Pipeline" width="100%">
</p>

</details>

## Foundational Capabilities for Smart Glasses

<details>
<summary><strong>Figure: Foundational capabilities and L0-L5 cross-capability level framework. </strong></summary>

<p align="center">
  <img src="assets/imgs/capabilities-L0-L5.png" alt="Survey Pipeline" width="100%">
</p>

</details>

## Application Scenes for Smart Glasses

## 📄 Citation
If you find our work helpful, please consider citing our paper:
```
@misc{zhang2026seeingactingsmartglasses,
      title={From Seeing to Acting: Smart Glasses as First-Person Intelligence Platforms}, 
      author={Jiangning Zhang and Haojun Chen and Yong Liu},
      year={2026},
      eprint={2608.24877},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2608.24877}, 
}
```

## 🤝 Contributing

Contributions are welcome. Please open an issue or submit a pull request to add or correct related smart-glasses products/platforms and works (datasets, benchmarks, methods, systems, and application resources). New entries should include a verifiable paper, official product/project page, or repository link.

## 🔗 Related Resources & Links

- [Awesome Egocentric Vision](https://github.com/sun254667/awesome-egocentric-vision)
- [Awsome Ego Equipments](https://github.com/EmbodiedAI-Group/awsome-ego-equipments)

## 🤗 Acknowledgments

We thank the authors, dataset and benchmark creators, product and platform developers, and open-source contributors whose work supports this survey.

---

<div align="center">
  <img src="https://img.shields.io/github/stars/zhangzjn/awesome-smart-glasses?style=social" alt="GitHub stars">
  <img src="https://img.shields.io/github/forks/zhangzjn/awesome-smart-glasses?style=social" alt="GitHub forks">
  <img src="https://img.shields.io/github/watchers/zhangzjn/awesome-smart-glasses?style=social" alt="GitHub watchers">
</div>

<div align="center">
  <strong>⭐ Leave this repository a star if you find it helpful! ⭐</strong>
</div>