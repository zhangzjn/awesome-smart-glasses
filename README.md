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
  - [4.1 Daily Situated Assistance](#41-daily-situated-assistance)
  - [4.2 Accessibility Assistance](#42-accessibility-assistance)
  - [4.3 Industrial Workflow Support](#43-industrial-workflow-support)
  - [4.4 Healthcare and Caregiving](#44-healthcare-and-caregiving)
  - [4.5 Education and Skills Training](#45-education-and-skills-training)
  - [4.6 Mobility and Transportation Safety](#46-mobility-and-transportation-safety)
  - [4.7 Social Interaction and Collaboration](#47-social-interaction-and-collaboration)
  - [4.8 Spatial Intelligence](#48-spatial-intelligence)
  - [4.9 Embodied Intelligence](#49-embodied-intelligence)
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
  <img src="assets/imgs/hardware-capability-axes.png" alt="Hardware Capability Axes" width="100%">
</p>

</details>

## Foundational Capabilities for Smart Glasses

<details>
<summary><strong>Figure: Foundational capabilities and L0-L5 cross-capability level framework. </strong></summary>

<p align="center">
  <img src="assets/imgs/capabilities-L0-L5.png" alt="Capabilities and L0-L5 Framework" width="100%">
</p>

</details>

> ⏰ We organize the works in chronological order, from the earliest to the latest.
🎨 Colored labels indicate <strong>seven foundational capabilities</strong> to which the work contributes: ![First-Person Perception](https://img.shields.io/badge/-First--Person%20Perception-2563eb?style=flat-square), ![Multimodal Context Modeling](https://img.shields.io/badge/-Multimodal%20Context%20Modeling-7c3aed?style=flat-square), ![Persistent Spatial State](https://img.shields.io/badge/-Persistent%20Spatial%20State-059669?style=flat-square), ![Auditable Long-Term Personal Memory](https://img.shields.io/badge/-Auditable%20Long--Term%20Personal%20Memory-d97706?style=flat-square), ![Situated Agentic Action](https://img.shields.io/badge/-Situated%20Agentic%20Action-dc2626?style=flat-square), ![Embodied Data Interfaces](https://img.shields.io/badge/-Embodied%20Data%20Interfaces-0f766e?style=flat-square), and ![Cross-Cutting Deployment Constraints](https://img.shields.io/badge/-Cross--Cutting%20Deployment%20Constraints-475569?style=flat-square).

| Capabilities | Paper Title | Link |
|---|---|---|
| ![Multimodal Context Modeling](https://img.shields.io/badge/-Multimodal%20Context%20Modeling-7c3aed?style=flat-square) | The AMI Meeting Corpus: A Pre-Announcement | [![Springer Nature](https://img.shields.io/badge/Springer%20Nature-Link-1f77b4?style=flat-square)](https://link.springer.com/chapter/10.1007/11677482_3) |
| ![Cross-Cutting Deployment Constraints](https://img.shields.io/badge/-Cross--Cutting%20Deployment%20Constraints-475569?style=flat-square) | In Situ with Bystanders of Augmented Reality Glasses: Perspectives on Recording and Privacy-Mediating Technologies | [![ACM DL](https://img.shields.io/badge/ACM%20DL-Link-0085ca?style=flat-square)](https://dl.acm.org/doi/10.1145/2556288.2557352) |
| ![Persistent Spatial State](https://img.shields.io/badge/-Persistent%20Spatial%20State-059669?style=flat-square) | NavCog: A Navigational Cognitive Assistant for the Blind | [![ACM DL](https://img.shields.io/badge/ACM%20DL-Link-0085ca?style=flat-square)](https://dl.acm.org/doi/10.1145/2935334.2935361) |
| ![Persistent Spatial State](https://img.shields.io/badge/-Persistent%20Spatial%20State-059669?style=flat-square) | ScanNet: Richly-Annotated 3D Reconstructions of Indoor Scenes | [![arXiv](https://img.shields.io/badge/arXiv-1702.04405-b31b1b?logo=arxiv)](https://arxiv.org/abs/1702.04405) |
| ![Persistent Spatial State](https://img.shields.io/badge/-Persistent%20Spatial%20State-059669?style=flat-square) | VINS-Mono: A Robust and Versatile Monocular Visual-Inertial State Estimator | [![arXiv](https://img.shields.io/badge/arXiv-1708.03852-b31b1b?logo=arxiv)](https://arxiv.org/abs/1708.03852) |
| ![Persistent Spatial State](https://img.shields.io/badge/-Persistent%20Spatial%20State-059669?style=flat-square) | Matterport3D: Learning from RGB-D Data in Indoor Environments | [![arXiv](https://img.shields.io/badge/arXiv-1709.06158-b31b1b?logo=arxiv)](https://arxiv.org/abs/1709.06158) |
| ![First-Person Perception](https://img.shields.io/badge/-First--Person%20Perception-2563eb?style=flat-square)<br>![Persistent Spatial State](https://img.shields.io/badge/-Persistent%20Spatial%20State-059669?style=flat-square) | VizWiz Grand Challenge: Answering Visual Questions from Blind People | [![arXiv](https://img.shields.io/badge/arXiv-1802.08218-b31b1b?logo=arxiv)](https://arxiv.org/abs/1802.08218) |
| ![Cross-Cutting Deployment Constraints](https://img.shields.io/badge/-Cross--Cutting%20Deployment%20Constraints-475569?style=flat-square) | Your Smart Glasses' Camera Bothers Me! Exploring Opt-In and Opt-Out Gestures for Privacy Mediation | [![ACM DL](https://img.shields.io/badge/ACM%20DL-Link-0085ca?style=flat-square)](https://dl.acm.org/doi/10.1145/3240167.3240174) |
| ![Multimodal Context Modeling](https://img.shields.io/badge/-Multimodal%20Context%20Modeling-7c3aed?style=flat-square) | AVA Active Speaker: An Audio-Visual Dataset for Active Speaker Detection | [![arXiv](https://img.shields.io/badge/arXiv-1901.01342-b31b1b?logo=arxiv)](https://arxiv.org/abs/1901.01342) |
| ![Embodied Data Interfaces](https://img.shields.io/badge/-Embodied%20Data%20Interfaces-0f766e?style=flat-square) | COIN: A Large-Scale Dataset for Comprehensive Instructional Video Analysis | [![arXiv](https://img.shields.io/badge/arXiv-1903.02874-b31b1b?logo=arxiv)](https://arxiv.org/abs/1903.02874) |
| ![Cross-Cutting Deployment Constraints](https://img.shields.io/badge/-Cross--Cutting%20Deployment%20Constraints-475569?style=flat-square) | Evaluating a Wearable Camera's Social Acceptability In-the-Wild | [![ACM DL](https://img.shields.io/badge/ACM%20DL-Link-0085ca?style=flat-square)](https://dl.acm.org/doi/10.1145/3290607.3312837) |
| ![First-Person Perception](https://img.shields.io/badge/-First--Person%20Perception-2563eb?style=flat-square)<br>![Persistent Spatial State](https://img.shields.io/badge/-Persistent%20Spatial%20State-059669?style=flat-square) | In the Eye of the Beholder: Joint Learning of Gaze and Actions in First Person Video | [![arXiv](https://img.shields.io/badge/arXiv-2006.00626-b31b1b?logo=arxiv)](https://arxiv.org/abs/2006.00626) |
| ![First-Person Perception](https://img.shields.io/badge/-First--Person%20Perception-2563eb?style=flat-square)<br>![Embodied Data Interfaces](https://img.shields.io/badge/-Embodied%20Data%20Interfaces-0f766e?style=flat-square) | Rescaling Egocentric Vision: Collection, Pipeline and Challenges for EPIC-KITCHENS-100 | [![arXiv](https://img.shields.io/badge/arXiv-2006.13256-b31b1b?logo=arxiv)](https://arxiv.org/abs/2006.13256) |
| ![First-Person Perception](https://img.shields.io/badge/-First--Person%20Perception-2563eb?style=flat-square)<br>![Embodied Data Interfaces](https://img.shields.io/badge/-Embodied%20Data%20Interfaces-0f766e?style=flat-square) | The IKEA ASM Dataset: Understanding People Assembling Furniture through Actions, Objects and Pose | [![arXiv](https://img.shields.io/badge/arXiv-2007.00394-b31b1b?logo=arxiv)](https://arxiv.org/abs/2007.00394) |
| ![Multimodal Context Modeling](https://img.shields.io/badge/-Multimodal%20Context%20Modeling-7c3aed?style=flat-square) | QMSum: A New Benchmark for Query-Based Multi-Domain Meeting Summarization | [![arXiv](https://img.shields.io/badge/arXiv-2104.05938-b31b1b?logo=arxiv)](https://arxiv.org/abs/2104.05938) |
| ![Persistent Spatial State](https://img.shields.io/badge/-Persistent%20Spatial%20State-059669?style=flat-square) | DROID-SLAM: Deep Visual SLAM for Monocular, Stereo, and RGB-D Cameras | [![arXiv](https://img.shields.io/badge/arXiv-2108.10869-b31b1b?logo=arxiv)](https://arxiv.org/abs/2108.10869) |
| ![First-Person Perception](https://img.shields.io/badge/-First--Person%20Perception-2563eb?style=flat-square)<br>![Embodied Data Interfaces](https://img.shields.io/badge/-Embodied%20Data%20Interfaces-0f766e?style=flat-square) | Ego4D: Around the World in 3,000 Hours of Egocentric Video | [![arXiv](https://img.shields.io/badge/arXiv-2110.07058-b31b1b?logo=arxiv)](https://arxiv.org/abs/2110.07058) |
| ![Multimodal Context Modeling](https://img.shields.io/badge/-Multimodal%20Context%20Modeling-7c3aed?style=flat-square)<br>![Embodied Data Interfaces](https://img.shields.io/badge/-Embodied%20Data%20Interfaces-0f766e?style=flat-square) | Assembly101: A Large-Scale Multi-View Video Dataset for Understanding Procedural Activities | [![arXiv](https://img.shields.io/badge/arXiv-2203.14712-b31b1b?logo=arxiv)](https://arxiv.org/abs/2203.14712) |
| ![Persistent Spatial State](https://img.shields.io/badge/-Persistent%20Spatial%20State-059669?style=flat-square) | LidSonic for Visually Impaired: Green Machine Learning-Based Assistive Smart Glasses with Smart App and Arduino | [![ResearchGate](https://img.shields.io/badge/ResearchGate-Link-1f77b4?style=flat-square)](https://www.researchgate.net/publication/359596956_LidSonic_for_Visually_Impaired_Green_Machine_Learning-Based_Assistive_Smart_Glasses_with_Smart_App_and_Arduino) |
| ![First-Person Perception](https://img.shields.io/badge/-First--Person%20Perception-2563eb?style=flat-square)<br>![Auditable Long-Term Personal Memory](https://img.shields.io/badge/-Auditable%20Long--Term%20Personal%20Memory-d97706?style=flat-square) | EgoTracks: A Long-Term Egocentric Visual Object Tracking Dataset | [![arXiv](https://img.shields.io/badge/arXiv-2301.03213-b31b1b?logo=arxiv)](https://arxiv.org/abs/2301.03213) |
| ![First-Person Perception](https://img.shields.io/badge/-First--Person%20Perception-2563eb?style=flat-square)<br>![Multimodal Context Modeling](https://img.shields.io/badge/-Multimodal%20Context%20Modeling-7c3aed?style=flat-square) | EPIC-Sounds: A Large-Scale Dataset of Actions That Sound | [![arXiv](https://img.shields.io/badge/arXiv-2302.00646-b31b1b?logo=arxiv)](https://arxiv.org/abs/2302.00646) |
| ![Persistent Spatial State](https://img.shields.io/badge/-Persistent%20Spatial%20State-059669?style=flat-square)<br>![Embodied Data Interfaces](https://img.shields.io/badge/-Embodied%20Data%20Interfaces-0f766e?style=flat-square) | Aria Digital Twin: A New Benchmark Dataset for Egocentric 3D Machine Perception | [![arXiv](https://img.shields.io/badge/arXiv-2306.06362-b31b1b?logo=arxiv)](https://arxiv.org/abs/2306.06362) |
| ![Multimodal Context Modeling](https://img.shields.io/badge/-Multimodal%20Context%20Modeling-7c3aed?style=flat-square) | EgoVLPv2: Egocentric Video-Language Pre-Training with Fusion in the Backbone | [![arXiv](https://img.shields.io/badge/arXiv-2307.05463-b31b1b?logo=arxiv)](https://arxiv.org/abs/2307.05463) |
| ![First-Person Perception](https://img.shields.io/badge/-First--Person%20Perception-2563eb?style=flat-square)<br>![Multimodal Context Modeling](https://img.shields.io/badge/-Multimodal%20Context%20Modeling-7c3aed?style=flat-square)<br>![Persistent Spatial State](https://img.shields.io/badge/-Persistent%20Spatial%20State-059669?style=flat-square)<br>![Embodied Data Interfaces](https://img.shields.io/badge/-Embodied%20Data%20Interfaces-0f766e?style=flat-square)<br>![Cross-Cutting Deployment Constraints](https://img.shields.io/badge/-Cross--Cutting%20Deployment%20Constraints-475569?style=flat-square) | Project Aria: A New Tool for Egocentric Multi-Modal AI Research | [![arXiv](https://img.shields.io/badge/arXiv-2308.13561-b31b1b?logo=arxiv)](https://arxiv.org/abs/2308.13561) |
| ![First-Person Perception](https://img.shields.io/badge/-First--Person%20Perception-2563eb?style=flat-square) | EgoObjects: A Large-Scale Egocentric Dataset for Fine-Grained Object Understanding | [![arXiv](https://img.shields.io/badge/arXiv-2309.08816-b31b1b?logo=arxiv)](https://arxiv.org/abs/2309.08816) |
| ![First-Person Perception](https://img.shields.io/badge/-First--Person%20Perception-2563eb?style=flat-square)<br>![Multimodal Context Modeling](https://img.shields.io/badge/-Multimodal%20Context%20Modeling-7c3aed?style=flat-square)<br>![Situated Agentic Action](https://img.shields.io/badge/-Situated%20Agentic%20Action-dc2626?style=flat-square)<br>![Embodied Data Interfaces](https://img.shields.io/badge/-Embodied%20Data%20Interfaces-0f766e?style=flat-square) | HoloAssist: An Egocentric Human Interaction Dataset for Interactive AI Assistants in the Real World | [![arXiv](https://img.shields.io/badge/arXiv-2309.17024-b31b1b?logo=arxiv)](https://arxiv.org/abs/2309.17024) |
| ![Cross-Cutting Deployment Constraints](https://img.shields.io/badge/-Cross--Cutting%20Deployment%20Constraints-475569?style=flat-square) | Head-Mounted Display Augmented Reality in Manufacturing: A Systematic Review | [![ACM DL](https://img.shields.io/badge/ACM%20DL-Link-0085ca?style=flat-square)](https://dl.acm.org/doi/10.1016/j.rcim.2023.102567) |
| ![Embodied Data Interfaces](https://img.shields.io/badge/-Embodied%20Data%20Interfaces-0f766e?style=flat-square) | Ego-Exo4D: Understanding Skilled Human Activity from First- and Third-Person Perspectives | [![arXiv](https://img.shields.io/badge/arXiv-2311.18259-b31b1b?logo=arxiv)](https://arxiv.org/abs/2311.18259) |
| ![Auditable Long-Term Personal Memory](https://img.shields.io/badge/-Auditable%20Long--Term%20Personal%20Memory-d97706?style=flat-square) | Memoro: Using Large Language Models to Realize a Concise Interface for Real-Time Memory Augmentation | [![arXiv](https://img.shields.io/badge/arXiv-2403.02135-b31b1b?logo=arxiv)](https://arxiv.org/abs/2403.02135) |
| ![Multimodal Context Modeling](https://img.shields.io/badge/-Multimodal%20Context%20Modeling-7c3aed?style=flat-square)<br>![Persistent Spatial State](https://img.shields.io/badge/-Persistent%20Spatial%20State-059669?style=flat-square)<br>![Auditable Long-Term Personal Memory](https://img.shields.io/badge/-Auditable%20Long--Term%20Personal%20Memory-d97706?style=flat-square)<br>![Embodied Data Interfaces](https://img.shields.io/badge/-Embodied%20Data%20Interfaces-0f766e?style=flat-square) | OpenEQA: Embodied Question Answering in the Era of Foundation Models | [![IEEE](https://img.shields.io/badge/IEEE-Link-0085ca?style=flat-square)](https://ieeexplore.ieee.org/document/10654928) |
| ![Embodied Data Interfaces](https://img.shields.io/badge/-Embodied%20Data%20Interfaces-0f766e?style=flat-square) | EgoMimic: Scaling Imitation Learning via Egocentric Video | [![arXiv](https://img.shields.io/badge/arXiv-2410.24221-b31b1b?logo=arxiv)](https://arxiv.org/abs/2410.24221) |
| ![First-Person Perception](https://img.shields.io/badge/-First--Person%20Perception-2563eb?style=flat-square)<br>![Multimodal Context Modeling](https://img.shields.io/badge/-Multimodal%20Context%20Modeling-7c3aed?style=flat-square)<br>![Cross-Cutting Deployment Constraints](https://img.shields.io/badge/-Cross--Cutting%20Deployment%20Constraints-475569?style=flat-square) | Vinci: A Real-Time Smart Assistant Based on Egocentric Vision-Language Model for Portable Devices | [![arXiv](https://img.shields.io/badge/arXiv-2412.21080-b31b1b?logo=arxiv)](https://arxiv.org/abs/2412.21080) |
| ![Multimodal Context Modeling](https://img.shields.io/badge/-Multimodal%20Context%20Modeling-7c3aed?style=flat-square)<br>![Auditable Long-Term Personal Memory](https://img.shields.io/badge/-Auditable%20Long--Term%20Personal%20Memory-d97706?style=flat-square) | EgoLife: Towards Egocentric Life Assistant | [![arXiv](https://img.shields.io/badge/arXiv-2503.03803-b31b1b?logo=arxiv)](https://arxiv.org/abs/2503.03803) |
| ![Embodied Data Interfaces](https://img.shields.io/badge/-Embodied%20Data%20Interfaces-0f766e?style=flat-square) | EgoDex: Learning Dexterous Manipulation from Large-Scale Egocentric Video | [![arXiv](https://img.shields.io/badge/arXiv-2505.11709-b31b1b?logo=arxiv)](https://arxiv.org/abs/2505.11709) |
| ![Multimodal Context Modeling](https://img.shields.io/badge/-Multimodal%20Context%20Modeling-7c3aed?style=flat-square)<br>![Situated Agentic Action](https://img.shields.io/badge/-Situated%20Agentic%20Action-dc2626?style=flat-square) | ContextAgent: Context-Aware Proactive LLM Agents with Open-World Sensory Perceptions | [![arXiv](https://img.shields.io/badge/arXiv-2505.14668-b31b1b?logo=arxiv)](https://arxiv.org/abs/2505.14668) |
| ![Embodied Data Interfaces](https://img.shields.io/badge/-Embodied%20Data%20Interfaces-0f766e?style=flat-square)<br>![Cross-Cutting Deployment Constraints](https://img.shields.io/badge/-Cross--Cutting%20Deployment%20Constraints-475569?style=flat-square) | EgoZero: Robot Learning from Smart Glasses | [![arXiv](https://img.shields.io/badge/arXiv-2505.20290-b31b1b?logo=arxiv)](https://arxiv.org/abs/2505.20290) |
| ![Multimodal Context Modeling](https://img.shields.io/badge/-Multimodal%20Context%20Modeling-7c3aed?style=flat-square) | AdaVideoRAG: Omni-Contextual Adaptive Retrieval-Augmented Efficient Long Video Understanding | [![arXiv](https://img.shields.io/badge/arXiv-2506.13589-b31b1b?logo=arxiv)](https://arxiv.org/abs/2506.13589) |
| ![Embodied Data Interfaces](https://img.shields.io/badge/-Embodied%20Data%20Interfaces-0f766e?style=flat-square) | EgoVLA: Learning Vision-Language-Action Models from Egocentric Human Videos | [![arXiv](https://img.shields.io/badge/arXiv-2507.12440-b31b1b?logo=arxiv)](https://arxiv.org/abs/2507.12440) |
| ![Auditable Long-Term Personal Memory](https://img.shields.io/badge/-Auditable%20Long--Term%20Personal%20Memory-d97706?style=flat-square)<br>![Cross-Cutting Deployment Constraints](https://img.shields.io/badge/-Cross--Cutting%20Deployment%20Constraints-475569?style=flat-square) | EgoTrigger: Toward Audio-Driven Image Capture for Human Memory Enhancement in All-Day Energy-Efficient Smart Glasses | [![arXiv](https://img.shields.io/badge/arXiv-2508.01915-b31b1b?logo=arxiv)](https://arxiv.org/abs/2508.01915) |
| ![Situated Agentic Action](https://img.shields.io/badge/-Situated%20Agentic%20Action-dc2626?style=flat-square) | AI for Service: Proactive Assistance with AI Glasses | [![arXiv](https://img.shields.io/badge/arXiv-2510.14359-b31b1b?logo=arxiv)](https://arxiv.org/abs/2510.14359) |
| ![Embodied Data Interfaces](https://img.shields.io/badge/-Embodied%20Data%20Interfaces-0f766e?style=flat-square) | EgoMI: Learning Active Vision and Whole-Body Manipulation from Egocentric Human Demonstrations | [![arXiv](https://img.shields.io/badge/arXiv-2511.00153-b31b1b?logo=arxiv)](https://arxiv.org/abs/2511.00153) |
| ![First-Person Perception](https://img.shields.io/badge/-First--Person%20Perception-2563eb?style=flat-square)<br>![Multimodal Context Modeling](https://img.shields.io/badge/-Multimodal%20Context%20Modeling-7c3aed?style=flat-square)<br>![Cross-Cutting Deployment Constraints](https://img.shields.io/badge/-Cross--Cutting%20Deployment%20Constraints-475569?style=flat-square) | WearVQA: A Visual Question Answering Benchmark for Wearables in Egocentric Authentic Real-World Scenarios | [![arXiv](https://img.shields.io/badge/arXiv-2511.22154-b31b1b?logo=arxiv)](https://arxiv.org/abs/2511.22154) |
| ![Multimodal Context Modeling](https://img.shields.io/badge/-Multimodal%20Context%20Modeling-7c3aed?style=flat-square)<br>![Cross-Cutting Deployment Constraints](https://img.shields.io/badge/-Cross--Cutting%20Deployment%20Constraints-475569?style=flat-square) | ROMA: Real-time Omni-Multimodal Assistant with Interactive Streaming Understanding | [![arXiv](https://img.shields.io/badge/arXiv-2601.10323-b31b1b?logo=arxiv)](https://arxiv.org/abs/2601.10323) |
| ![Multimodal Context Modeling](https://img.shields.io/badge/-Multimodal%20Context%20Modeling-7c3aed?style=flat-square) | Agentic Very Long Video Understanding | [![arXiv](https://img.shields.io/badge/arXiv-2601.18157-b31b1b?logo=arxiv)](https://arxiv.org/abs/2601.18157) |
| ![Auditable Long-Term Personal Memory](https://img.shields.io/badge/-Auditable%20Long--Term%20Personal%20Memory-d97706?style=flat-square)<br>![Cross-Cutting Deployment Constraints](https://img.shields.io/badge/-Cross--Cutting%20Deployment%20Constraints-475569?style=flat-square) | VisGuardian: A Lightweight Group-based Privacy Control Technique For Front Camera Data From AR Glasses in Home Environments | [![arXiv](https://img.shields.io/badge/arXiv-2601.19502-b31b1b?logo=arxiv)](https://arxiv.org/abs/2601.19502) |
| ![First-Person Perception](https://img.shields.io/badge/-First--Person%20Perception-2563eb?style=flat-square)<br>![Cross-Cutting Deployment Constraints](https://img.shields.io/badge/-Cross--Cutting%20Deployment%20Constraints-475569?style=flat-square) | Evaluating OCR Performance for Assistive Technology: Effects of Walking Speed, Camera Placement, and Camera Type | [![arXiv](https://img.shields.io/badge/arXiv-2602.02223-b31b1b?logo=arxiv)](https://arxiv.org/abs/2602.02223) |
| ![Persistent Spatial State](https://img.shields.io/badge/-Persistent%20Spatial%20State-059669?style=flat-square)<br>![Embodied Data Interfaces](https://img.shields.io/badge/-Embodied%20Data%20Interfaces-0f766e?style=flat-square)<br>![Cross-Cutting Deployment Constraints](https://img.shields.io/badge/-Cross--Cutting%20Deployment%20Constraints-475569?style=flat-square) | LEVIO: Lightweight Embedded Visual Inertial Odometry for Resource-Constrained Devices | [![arXiv](https://img.shields.io/badge/arXiv-2602.03294-b31b1b?logo=arxiv)](https://arxiv.org/abs/2602.03294) |
| ![First-Person Perception](https://img.shields.io/badge/-First--Person%20Perception-2563eb?style=flat-square)<br>![Multimodal Context Modeling](https://img.shields.io/badge/-Multimodal%20Context%20Modeling-7c3aed?style=flat-square)<br>![Cross-Cutting Deployment Constraints](https://img.shields.io/badge/-Cross--Cutting%20Deployment%20Constraints-475569?style=flat-square) | GLIMPSE: Real-Time Text Recognition and Contextual Understanding for VQA in Wearables | [![arXiv](https://img.shields.io/badge/arXiv-2602.13479-b31b1b?logo=arxiv)](https://arxiv.org/abs/2602.13479) |
| ![First-Person Perception](https://img.shields.io/badge/-First--Person%20Perception-2563eb?style=flat-square)<br>![Multimodal Context Modeling](https://img.shields.io/badge/-Multimodal%20Context%20Modeling-7c3aed?style=flat-square)<br>![Cross-Cutting Deployment Constraints](https://img.shields.io/badge/-Cross--Cutting%20Deployment%20Constraints-475569?style=flat-square) | SAW-Bench: Learning Situated Awareness in the Real World | [![arXiv](https://img.shields.io/badge/arXiv-2602.16682-b31b1b?logo=arxiv)](https://arxiv.org/abs/2602.16682) |
| ![Multimodal Context Modeling](https://img.shields.io/badge/-Multimodal%20Context%20Modeling-7c3aed?style=flat-square)<br>![Cross-Cutting Deployment Constraints](https://img.shields.io/badge/-Cross--Cutting%20Deployment%20Constraints-475569?style=flat-square) | Conversational Successes and Breakdowns in Everyday Smart Glasses Use | [![arXiv](https://img.shields.io/badge/arXiv-2602.22340-b31b1b?logo=arxiv)](https://arxiv.org/abs/2602.22340) |
| ![Auditable Long-Term Personal Memory](https://img.shields.io/badge/-Auditable%20Long--Term%20Personal%20Memory-d97706?style=flat-square)<br>![Cross-Cutting Deployment Constraints](https://img.shields.io/badge/-Cross--Cutting%20Deployment%20Constraints-475569?style=flat-square) | Exploring Multimodal LMMs for Online Episodic Memory Question Answering on the Edge | [![arXiv](https://img.shields.io/badge/arXiv-2602.22455-b31b1b?logo=arxiv)](https://arxiv.org/abs/2602.22455) |
| ![First-Person Perception](https://img.shields.io/badge/-First--Person%20Perception-2563eb?style=flat-square)<br>![Multimodal Context Modeling](https://img.shields.io/badge/-Multimodal%20Context%20Modeling-7c3aed?style=flat-square)<br>![Cross-Cutting Deployment Constraints](https://img.shields.io/badge/-Cross--Cutting%20Deployment%20Constraints-475569?style=flat-square) | SUPERGLASSES: Benchmarking Vision Language Models as Intelligent Agents for AI Smart Glasses | [![arXiv](https://img.shields.io/badge/arXiv-2602.22683-b31b1b?logo=arxiv)](https://arxiv.org/abs/2602.22683) |
| ![First-Person Perception](https://img.shields.io/badge/-First--Person%20Perception-2563eb?style=flat-square)<br>![Embodied Data Interfaces](https://img.shields.io/badge/-Embodied%20Data%20Interfaces-0f766e?style=flat-square)<br>![Cross-Cutting Deployment Constraints](https://img.shields.io/badge/-Cross--Cutting%20Deployment%20Constraints-475569?style=flat-square) | AoE: Always-On Egocentric Human Video Collection for Embodied AI | [![arXiv](https://img.shields.io/badge/arXiv-2602.23893-b31b1b?logo=arxiv)](https://arxiv.org/abs/2602.23893) |
| ![Situated Agentic Action](https://img.shields.io/badge/-Situated%20Agentic%20Action-dc2626?style=flat-square) | Egocentric Co-Pilot: Web-Native Smart-Glasses Agents for Assistive Egocentric AI | [![arXiv](https://img.shields.io/badge/arXiv-2603.01104-b31b1b?logo=arxiv)](https://arxiv.org/abs/2603.01104) |
| ![Auditable Long-Term Personal Memory](https://img.shields.io/badge/-Auditable%20Long--Term%20Personal%20Memory-d97706?style=flat-square)<br>![Cross-Cutting Deployment Constraints](https://img.shields.io/badge/-Cross--Cutting%20Deployment%20Constraints-475569?style=flat-square) | Mind the Gap: Mapping Wearer--Bystander Privacy Tensions and Context-Adaptive Pathways for Camera Glasses | [![arXiv](https://img.shields.io/badge/arXiv-2603.04930-b31b1b?logo=arxiv)](https://arxiv.org/abs/2603.04930) |
| ![First-Person Perception](https://img.shields.io/badge/-First--Person%20Perception-2563eb?style=flat-square)<br>![Embodied Data Interfaces](https://img.shields.io/badge/-Embodied%20Data%20Interfaces-0f766e?style=flat-square) | Ego-1K--A Large-Scale Multiview Video Dataset for Egocentric Vision | [![arXiv](https://img.shields.io/badge/arXiv-2603.13741-b31b1b?logo=arxiv)](https://arxiv.org/abs/2603.13741) |
| ![Persistent Spatial State](https://img.shields.io/badge/-Persistent%20Spatial%20State-059669?style=flat-square) | EgoForge: Goal-Directed Egocentric World Simulator | [![arXiv](https://img.shields.io/badge/arXiv-2603.20169-b31b1b?logo=arxiv)](https://arxiv.org/abs/2603.20169) |
| ![Embodied Data Interfaces](https://img.shields.io/badge/-Embodied%20Data%20Interfaces-0f766e?style=flat-square) | UniDex: A Robot Foundation Suite for Universal Dexterous Hand Control from Egocentric Human Videos | [![arXiv](https://img.shields.io/badge/arXiv-2603.22264-b31b1b?logo=arxiv)](https://arxiv.org/abs/2603.22264) |
| ![Situated Agentic Action](https://img.shields.io/badge/-Situated%20Agentic%20Action-dc2626?style=flat-square) | Ego2Web: A Web Agent Benchmark Grounded in Egocentric Videos | [![arXiv](https://img.shields.io/badge/arXiv-2603.22529-b31b1b?logo=arxiv)](https://arxiv.org/abs/2603.22529) |
| ![Persistent Spatial State](https://img.shields.io/badge/-Persistent%20Spatial%20State-059669?style=flat-square) | Pandora: Articulated 3D Scene Graphs from Egocentric Vision | [![arXiv](https://img.shields.io/badge/arXiv-2603.28732-b31b1b?logo=arxiv)](https://arxiv.org/abs/2603.28732) |
| ![Auditable Long-Term Personal Memory](https://img.shields.io/badge/-Auditable%20Long--Term%20Personal%20Memory-d97706?style=flat-square)<br>![Situated Agentic Action](https://img.shields.io/badge/-Situated%20Agentic%20Action-dc2626?style=flat-square) | Ego-Grounding for Personalized Question-Answering in Egocentric Videos | [![arXiv](https://img.shields.io/badge/arXiv-2604.01966-b31b1b?logo=arxiv)](https://arxiv.org/abs/2604.01966) |
| ![Situated Agentic Action](https://img.shields.io/badge/-Situated%20Agentic%20Action-dc2626?style=flat-square)<br>![Cross-Cutting Deployment Constraints](https://img.shields.io/badge/-Cross--Cutting%20Deployment%20Constraints-475569?style=flat-square) | VisionClaw: Always-On AI Agents through Smart Glasses | [![arXiv](https://img.shields.io/badge/arXiv-2604.03486-b31b1b?logo=arxiv)](https://arxiv.org/abs/2604.03486) |
| ![Multimodal Context Modeling](https://img.shields.io/badge/-Multimodal%20Context%20Modeling-7c3aed?style=flat-square)<br>![Cross-Cutting Deployment Constraints](https://img.shields.io/badge/-Cross--Cutting%20Deployment%20Constraints-475569?style=flat-square) | Active Noise Cancellation on Open-Ear Smart Glasses | [![arXiv](https://img.shields.io/badge/arXiv-2604.05519-b31b1b?logo=arxiv)](https://arxiv.org/abs/2604.05519) |
| ![Multimodal Context Modeling](https://img.shields.io/badge/-Multimodal%20Context%20Modeling-7c3aed?style=flat-square) | Reshaping Inclusive Interpersonal Dynamics through Smart Glasses in Mixed-Vision Social Activities | [![arXiv](https://img.shields.io/badge/arXiv-2604.07232-b31b1b?logo=arxiv)](https://arxiv.org/abs/2604.07232) |
| ![Embodied Data Interfaces](https://img.shields.io/badge/-Embodied%20Data%20Interfaces-0f766e?style=flat-square) | ActiveGlasses: Learning Manipulation with Active Vision from Ego-Centric Human Demonstration | [![arXiv](https://img.shields.io/badge/arXiv-2604.08534-b31b1b?logo=arxiv)](https://arxiv.org/abs/2604.08534) |
| ![First-Person Perception](https://img.shields.io/badge/-First--Person%20Perception-2563eb?style=flat-square)<br>![Persistent Spatial State](https://img.shields.io/badge/-Persistent%20Spatial%20State-059669?style=flat-square) | Do MLLMs Understand Pointing? Benchmarking and Enhancing Referential Reasoning in Egocentric Vision | [![arXiv](https://img.shields.io/badge/arXiv-2604.21461-b31b1b?logo=arxiv)](https://arxiv.org/abs/2604.21461) |
| ![Cross-Cutting Deployment Constraints](https://img.shields.io/badge/-Cross--Cutting%20Deployment%20Constraints-475569?style=flat-square) | UNSEEN: A Cross-Stack LLM Unlearning Defense against AR-LLM Social Engineering Attacks | [![arXiv](https://img.shields.io/badge/arXiv-2604.23141-b31b1b?logo=arxiv)](https://arxiv.org/abs/2604.23141) |
| ![Situated Agentic Action](https://img.shields.io/badge/-Situated%20Agentic%20Action-dc2626?style=flat-square)<br>![Cross-Cutting Deployment Constraints](https://img.shields.io/badge/-Cross--Cutting%20Deployment%20Constraints-475569?style=flat-square) | PhySE: A Psychological Framework for Real-Time AR-LLM Social Engineering Attacks | [![arXiv](https://img.shields.io/badge/arXiv-2604.23148-b31b1b?logo=arxiv)](https://arxiv.org/abs/2604.23148) |
| ![Situated Agentic Action](https://img.shields.io/badge/-Situated%20Agentic%20Action-dc2626?style=flat-square) | Intention-Aware Semantic Agent Communications for AI Glasses | [![arXiv](https://img.shields.io/badge/arXiv-2604.23691-b31b1b?logo=arxiv)](https://arxiv.org/abs/2604.23691) |
| ![Situated Agentic Action](https://img.shields.io/badge/-Situated%20Agentic%20Action-dc2626?style=flat-square) | Pro $^2$ Assist: Continuous Step-Aware Proactive Assistance with Multimodal Egocentric Perception for Long-Horizon Procedural Tasks | [![arXiv](https://img.shields.io/badge/arXiv-2605.04227-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.04227) |
| ![Embodied Data Interfaces](https://img.shields.io/badge/-Embodied%20Data%20Interfaces-0f766e?style=flat-square) | HumanNet: Scaling Human-Centric Video Learning to One Million Hours | [![arXiv](https://img.shields.io/badge/arXiv-2605.06747-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.06747) |
| ![Situated Agentic Action](https://img.shields.io/badge/-Situated%20Agentic%20Action-dc2626?style=flat-square) | EgoPro-Bench: Benchmarking Personalized Proactive Interaction in Egocentric Video Streams | [![arXiv](https://img.shields.io/badge/arXiv-2605.07299-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.07299) |
| ![Multimodal Context Modeling](https://img.shields.io/badge/-Multimodal%20Context%20Modeling-7c3aed?style=flat-square)<br>![Auditable Long-Term Personal Memory](https://img.shields.io/badge/-Auditable%20Long--Term%20Personal%20Memory-d97706?style=flat-square) | EgoMemReason: A Memory-Driven Reasoning Benchmark for Long-Horizon Egocentric Video Understanding | [![arXiv](https://img.shields.io/badge/arXiv-2605.09874-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.09874) |
| ![Auditable Long-Term Personal Memory](https://img.shields.io/badge/-Auditable%20Long--Term%20Personal%20Memory-d97706?style=flat-square)<br>![Cross-Cutting Deployment Constraints](https://img.shields.io/badge/-Cross--Cutting%20Deployment%20Constraints-475569?style=flat-square) | Position: Life-Logging Video Streams Make the Privacy-Utility Trade-off Inevitable | [![arXiv](https://img.shields.io/badge/arXiv-2605.10404-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.10404) |
| ![Multimodal Context Modeling](https://img.shields.io/badge/-Multimodal%20Context%20Modeling-7c3aed?style=flat-square)<br>![Auditable Long-Term Personal Memory](https://img.shields.io/badge/-Auditable%20Long--Term%20Personal%20Memory-d97706?style=flat-square)<br>![Situated Agentic Action](https://img.shields.io/badge/-Situated%20Agentic%20Action-dc2626?style=flat-square) | Personal Visual Context Learning in Large Multimodal Models | [![arXiv](https://img.shields.io/badge/arXiv-2605.10936-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.10936) |
| ![Persistent Spatial State](https://img.shields.io/badge/-Persistent%20Spatial%20State-059669?style=flat-square)<br>![Cross-Cutting Deployment Constraints](https://img.shields.io/badge/-Cross--Cutting%20Deployment%20Constraints-475569?style=flat-square) | Urban Risk-Aware Navigation via VQA-Based Event Maps for People with Low Vision | [![arXiv](https://img.shields.io/badge/arXiv-2605.11782-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.11782) |
| ![First-Person Perception](https://img.shields.io/badge/-First--Person%20Perception-2563eb?style=flat-square)<br>![Embodied Data Interfaces](https://img.shields.io/badge/-Embodied%20Data%20Interfaces-0f766e?style=flat-square)<br>![Cross-Cutting Deployment Constraints](https://img.shields.io/badge/-Cross--Cutting%20Deployment%20Constraints-475569?style=flat-square) | EgoKit: Towards Unified Low-Cost Egocentric Data Collection with Heterogeneous Devices | [![arXiv](https://img.shields.io/badge/arXiv-2605.16797-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.16797) |
| ![Multimodal Context Modeling](https://img.shields.io/badge/-Multimodal%20Context%20Modeling-7c3aed?style=flat-square)<br>![Auditable Long-Term Personal Memory](https://img.shields.io/badge/-Auditable%20Long--Term%20Personal%20Memory-d97706?style=flat-square) | EgoExoMem: Cross-View Memory Reasoning over Synchronized Egocentric and Exocentric Videos | [![arXiv](https://img.shields.io/badge/arXiv-2605.18734-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.18734) |
| ![Persistent Spatial State](https://img.shields.io/badge/-Persistent%20Spatial%20State-059669?style=flat-square) | EgoProx: Evaluating MLLMs on Egocentric 3D Proximity Reasoning Across a Cognitive Hierarchy | [![arXiv](https://img.shields.io/badge/arXiv-2605.24456-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.24456) |
| ![Embodied Data Interfaces](https://img.shields.io/badge/-Embodied%20Data%20Interfaces-0f766e?style=flat-square) | HumanEgo: Zero-Shot Robot Learning from Minutes of Human Egocentric Videos | [![arXiv](https://img.shields.io/badge/arXiv-2605.24934-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.24934) |
| ![Multimodal Context Modeling](https://img.shields.io/badge/-Multimodal%20Context%20Modeling-7c3aed?style=flat-square)<br>![Situated Agentic Action](https://img.shields.io/badge/-Situated%20Agentic%20Action-dc2626?style=flat-square)<br>![Cross-Cutting Deployment Constraints](https://img.shields.io/badge/-Cross--Cutting%20Deployment%20Constraints-475569?style=flat-square) | IPIBench: Evaluating Interactive Proactive Intelligence of MLLMs under Continuous Streams | [![arXiv](https://img.shields.io/badge/arXiv-2605.27074-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.27074) |
| ![Multimodal Context Modeling](https://img.shields.io/badge/-Multimodal%20Context%20Modeling-7c3aed?style=flat-square)<br>![Auditable Long-Term Personal Memory](https://img.shields.io/badge/-Auditable%20Long--Term%20Personal%20Memory-d97706?style=flat-square)<br>![Cross-Cutting Deployment Constraints](https://img.shields.io/badge/-Cross--Cutting%20Deployment%20Constraints-475569?style=flat-square) | EGOSTREAM: A Diagnostic Benchmark for Streaming Episodic Memory in Egocentric Vision | [![arXiv](https://img.shields.io/badge/arXiv-2605.31557-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.31557) |
| ![Situated Agentic Action](https://img.shields.io/badge/-Situated%20Agentic%20Action-dc2626?style=flat-square)<br>![Cross-Cutting Deployment Constraints](https://img.shields.io/badge/-Cross--Cutting%20Deployment%20Constraints-475569?style=flat-square) | Plan, Watch, Recover: A Benchmark and Architectures for Proactive Procedural Assistance | [![arXiv](https://img.shields.io/badge/arXiv-2606.04970-b31b1b?logo=arxiv)](https://arxiv.org/abs/2606.04970) |
| ![Embodied Data Interfaces](https://img.shields.io/badge/-Embodied%20Data%20Interfaces-0f766e?style=flat-square) | ActiveMimic: Egocentric Video Pretraining with Active Perception | [![arXiv](https://img.shields.io/badge/arXiv-2606.06194-b31b1b?logo=arxiv)](https://arxiv.org/abs/2606.06194) |
| ![Cross-Cutting Deployment Constraints](https://img.shields.io/badge/-Cross--Cutting%20Deployment%20Constraints-475569?style=flat-square) | OpenGlass: Ultra-Low-Power On-Device AI Eyewear with Event-Based Vision | [![arXiv](https://img.shields.io/badge/arXiv-2606.07431-b31b1b?logo=arxiv)](https://arxiv.org/abs/2606.07431) |
| ![Embodied Data Interfaces](https://img.shields.io/badge/-Embodied%20Data%20Interfaces-0f766e?style=flat-square) | EgoTactile: Learning Grasp Pressure for Everyday Objects from Egocentric Video | [![arXiv](https://img.shields.io/badge/arXiv-2606.09243-b31b1b?logo=arxiv)](https://arxiv.org/abs/2606.09243) |
| ![Multimodal Context Modeling](https://img.shields.io/badge/-Multimodal%20Context%20Modeling-7c3aed?style=flat-square)<br>![Auditable Long-Term Personal Memory](https://img.shields.io/badge/-Auditable%20Long--Term%20Personal%20Memory-d97706?style=flat-square) | H2HMem: A Multimodal Memory Benchmark for Agents in Human-Human Interactions | [![arXiv](https://img.shields.io/badge/arXiv-2606.09461-b31b1b?logo=arxiv)](https://arxiv.org/abs/2606.09461) |
| ![Situated Agentic Action](https://img.shields.io/badge/-Situated%20Agentic%20Action-dc2626?style=flat-square) | Streaming Interventions: Can Video Large Language Models Correct Mistakes as They Occur? | [![arXiv](https://img.shields.io/badge/arXiv-2606.09547-b31b1b?logo=arxiv)](https://arxiv.org/abs/2606.09547) |
| ![Persistent Spatial State](https://img.shields.io/badge/-Persistent%20Spatial%20State-059669?style=flat-square) | SpatialWorld: Benchmarking Interactive Spatial Reasoning of Multimodal Agents in Real-World Tasks | [![arXiv](https://img.shields.io/badge/arXiv-2606.09669-b31b1b?logo=arxiv)](https://arxiv.org/abs/2606.09669) |
| ![Embodied Data Interfaces](https://img.shields.io/badge/-Embodied%20Data%20Interfaces-0f766e?style=flat-square) | EgoEngine: From Egocentric Human Videos to High-Fidelity Dexterous Robot Demonstrations | [![arXiv](https://img.shields.io/badge/arXiv-2606.12604-b31b1b?logo=arxiv)](https://arxiv.org/abs/2606.12604) |
| ![Cross-Cutting Deployment Constraints](https://img.shields.io/badge/-Cross--Cutting%20Deployment%20Constraints-475569?style=flat-square) | EPIC: A System Framework for Efficient Egocentric Perception on Embodied AR Glasses | [![arXiv](https://img.shields.io/badge/arXiv-2606.15859-b31b1b?logo=arxiv)](https://arxiv.org/abs/2606.15859) |
| ![First-Person Perception](https://img.shields.io/badge/-First--Person%20Perception-2563eb?style=flat-square)<br>![Multimodal Context Modeling](https://img.shields.io/badge/-Multimodal%20Context%20Modeling-7c3aed?style=flat-square)<br>![Situated Agentic Action](https://img.shields.io/badge/-Situated%20Agentic%20Action-dc2626?style=flat-square)<br>![Cross-Cutting Deployment Constraints](https://img.shields.io/badge/-Cross--Cutting%20Deployment%20Constraints-475569?style=flat-square) | EgoSAT: A Comprehensive Benchmark of Egocentric Streaming Interaction Understanding | [![arXiv](https://img.shields.io/badge/arXiv-2606.24422-b31b1b?logo=arxiv)](https://arxiv.org/abs/2606.24422) |
| ![Cross-Cutting Deployment Constraints](https://img.shields.io/badge/-Cross--Cutting%20Deployment%20Constraints-475569?style=flat-square) | OpenGlass: A Sensing-Computing Split Architecture for Local MLLM-Driven Real-Time Visual Assistance | [![arXiv](https://img.shields.io/badge/arXiv-2607.03213-b31b1b?logo=arxiv)](https://arxiv.org/abs/2607.03213) |
| ![Auditable Long-Term Personal Memory](https://img.shields.io/badge/-Auditable%20Long--Term%20Personal%20Memory-d97706?style=flat-square) | LightMem-Ego: Your AI Memory for Everyday Life | [![arXiv](https://img.shields.io/badge/arXiv-2607.11487-b31b1b?logo=arxiv)](https://arxiv.org/abs/2607.11487) |
| ![First-Person Perception](https://img.shields.io/badge/-First--Person%20Perception-2563eb?style=flat-square)<br>![Embodied Data Interfaces](https://img.shields.io/badge/-Embodied%20Data%20Interfaces-0f766e?style=flat-square)<br>![Cross-Cutting Deployment Constraints](https://img.shields.io/badge/-Cross--Cutting%20Deployment%20Constraints-475569?style=flat-square) | Open-AoE: An Open Egocentric Manipulation Dataset and Toolchain for Embodied Learning | [![arXiv](https://img.shields.io/badge/arXiv-2607.14183-b31b1b?logo=arxiv)](https://arxiv.org/abs/2607.14183) |
| ![Embodied Data Interfaces](https://img.shields.io/badge/-Embodied%20Data%20Interfaces-0f766e?style=flat-square) | EgoExoMoCap: Distributed Ego-Exo Human Motion Capture | [![arXiv](https://img.shields.io/badge/arXiv-2607.15868-b31b1b?logo=arxiv)](https://arxiv.org/abs/2607.15868) |
| ![Auditable Long-Term Personal Memory](https://img.shields.io/badge/-Auditable%20Long--Term%20Personal%20Memory-d97706?style=flat-square) | EgoMonth: A Month-Level Egocentric Video Benchmark for Long-Term Spatiotemporal Memory | [![arXiv](https://img.shields.io/badge/arXiv-2608.13113-b31b1b?logo=arxiv)](https://arxiv.org/abs/2608.13113) |

## Application Scenes for Smart Glasses

> ⏰ For each application scene, we organize the works in chronological order, from the earliest to the latest.

### 4.1 Daily Situated Assistance

| Paper Title | Link |
|---|---|
| Vinci: A Real-Time Smart Assistant Based on Egocentric Vision-Language Model for Portable Devices | [![arXiv](https://img.shields.io/badge/arXiv-2412.21080-b31b1b?logo=arxiv)](https://arxiv.org/abs/2412.21080) |
| AiGet: Transforming Everyday Moments into Hidden Knowledge Discovery with AI Assistance on Smart Glasses | [![arXiv](https://img.shields.io/badge/arXiv-2501.16240-b31b1b?logo=arxiv)](https://arxiv.org/abs/2501.16240) |
| EgoLife: Towards Egocentric Life Assistant | [![arXiv](https://img.shields.io/badge/arXiv-2503.03803-b31b1b?logo=arxiv)](https://arxiv.org/abs/2503.03803) |
| ContextAgent: Context-Aware Proactive LLM Agents with Open-World Sensory Perceptions | [![arXiv](https://img.shields.io/badge/arXiv-2505.14668-b31b1b?logo=arxiv)](https://arxiv.org/abs/2505.14668) |
| AI for Service: Proactive Assistance with AI Glasses | [![arXiv](https://img.shields.io/badge/arXiv-2510.14359-b31b1b?logo=arxiv)](https://arxiv.org/abs/2510.14359) |
| TeleEgo: Benchmarking Egocentric AI Assistants in the Wild | [![arXiv](https://img.shields.io/badge/arXiv-2510.23981-b31b1b?logo=arxiv)](https://arxiv.org/abs/2510.23981) |
| WearVQA: A Visual Question Answering Benchmark for Wearables in Egocentric Authentic Real-world Scenarios | [![arXiv](https://img.shields.io/badge/arXiv-2511.22154-b31b1b?logo=arxiv)](https://arxiv.org/abs/2511.22154) |
| ROMA: Real-time Omni-Multimodal Assistant with Interactive Streaming Understanding | [![arXiv](https://img.shields.io/badge/arXiv-2601.10323-b31b1b?logo=arxiv)](https://arxiv.org/abs/2601.10323) |
| GLIMPSE: Real-Time Text Recognition and Contextual Understanding for VQA in Wearables | [![arXiv](https://img.shields.io/badge/arXiv-2602.13479-b31b1b?logo=arxiv)](https://arxiv.org/abs/2602.13479) |
| SAW-Bench: Learning Situated Awareness in the Real World | [![arXiv](https://img.shields.io/badge/arXiv-2602.16682-b31b1b?logo=arxiv)](https://arxiv.org/abs/2602.16682) |
| Exploring Multimodal LMMs for Online Episodic Memory Question Answering on the Edge | [![arXiv](https://img.shields.io/badge/arXiv-2602.22455-b31b1b?logo=arxiv)](https://arxiv.org/abs/2602.22455) |
| SUPERGLASSES: Benchmarking Vision Language Models as Intelligent Agents for AI Smart Glasses | [![arXiv](https://img.shields.io/badge/arXiv-2602.22683-b31b1b?logo=arxiv)](https://arxiv.org/abs/2602.22683) |
| Egocentric Co-Pilot: Web-Native Smart-Glasses Agents for Assistive Egocentric AI | [![arXiv](https://img.shields.io/badge/arXiv-2603.01104-b31b1b?logo=arxiv)](https://arxiv.org/abs/2603.01104) |
| Ego2Web: A Web Agent Benchmark Grounded in Egocentric Videos | [![arXiv](https://img.shields.io/badge/arXiv-2603.22529-b31b1b?logo=arxiv)](https://arxiv.org/abs/2603.22529) |
| VisionClaw: Always-On AI Agents through Smart Glasses | [![arXiv](https://img.shields.io/badge/arXiv-2604.03486-b31b1b?logo=arxiv)](https://arxiv.org/abs/2604.03486) |
| Intention-Aware Semantic Agent Communications for AI Glasses | [![arXiv](https://img.shields.io/badge/arXiv-2604.23691-b31b1b?logo=arxiv)](https://arxiv.org/abs/2604.23691) |
| EgoMemReason: A Memory-Driven Reasoning Benchmark for Long-Horizon Egocentric Video Understanding | [![arXiv](https://img.shields.io/badge/arXiv-2605.09874-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.09874) |
| Personal Visual Context Learning in Large Multimodal Models | [![arXiv](https://img.shields.io/badge/arXiv-2605.10936-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.10936) |
| EgoPro-Bench: Benchmarking Personalized Proactive Interaction in Egocentric Video Streams | [![arXiv](https://img.shields.io/badge/arXiv-2605.07299-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.07299) |
| IPIBench: Evaluating Interactive Proactive Intelligence of MLLMs under Continuous Streams | [![arXiv](https://img.shields.io/badge/arXiv-2605.27074-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.27074) |
| EGOSTREAM: A Diagnostic Benchmark for Streaming Episodic Memory in Egocentric Vision | [![arXiv](https://img.shields.io/badge/arXiv-2605.31557-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.31557) |
| EgoSAT: A Comprehensive Benchmark of Egocentric Streaming Interaction Understanding | [![arXiv](https://img.shields.io/badge/arXiv-2606.24422-b31b1b?logo=arxiv)](https://arxiv.org/abs/2606.24422) |
| OpenGlass: A Sensing-Computing Split Architecture for Local MLLM-Driven Real-Time Visual Assistance | [![arXiv](https://img.shields.io/badge/arXiv-2607.03213-b31b1b?logo=arxiv)](https://arxiv.org/abs/2607.03213) |
| LightMem-Ego: Your AI Memory for Everyday Life | [![arXiv](https://img.shields.io/badge/arXiv-2607.11487-b31b1b?logo=arxiv)](https://arxiv.org/abs/2607.11487) |
| EgoMonth: A Month-Level Egocentric Video Benchmark for Long-Term Spatiotemporal Memory | [![arXiv](https://img.shields.io/badge/arXiv-2608.13113-b31b1b?logo=arxiv)](https://arxiv.org/abs/2608.13113) |

### 4.2 Accessibility Assistance

| Paper Title | Link |
|---|---|
| NavCog: A Navigational Cognitive Assistant for the Blind | [![ACM DL](https://img.shields.io/badge/ACM%20DL-Link-0085ca?style=flat-square)](https://dl.acm.org/doi/10.1145/2935334.2935361) |
| VizWiz Grand Challenge: Answering Visual Questions from Blind People | [![arXiv](https://img.shields.io/badge/arXiv-1802.08218-b31b1b?logo=arxiv)](https://arxiv.org/abs/1802.08218) |
| The Effectiveness of Visual and Audio Wayfinding Guidance on Smartglasses for People with Low Vision | [![ACM DL](https://img.shields.io/badge/ACM%20DL-Link-0085ca?style=flat-square)](https://dl.acm.org/doi/10.1145/3313831.3376516) |
| LidSonic for Visually Impaired: Green Machine Learning-Based Assistive Smart Glasses with Smart App and Arduino | [![ResearchGate](https://img.shields.io/badge/ResearchGate-Link-1f77b4?style=flat-square)](https://www.researchgate.net/publication/359596956_LidSonic_for_Visually_Impaired_Green_Machine_Learning-Based_Assistive_Smart_Glasses_with_Smart_App_and_Arduino) |
| EgoBlind: Towards Egocentric Visual Assistance for the Blind | [![arXiv](https://img.shields.io/badge/arXiv-2503.08221-b31b1b?logo=arxiv)](https://arxiv.org/abs/2503.08221) |
| Exploring LLM-Based Assistants with Smart Glasses for the Visually Impaired | [![ACM DL](https://img.shields.io/badge/ACM%20DL-Link-0085ca?style=flat-square)](https://dl.acm.org/doi/10.1145/3769102.3774892) |
| Evaluating OCR Performance for Assistive Technology: Effects of Walking Speed, Camera Placement, and Camera Type | [![arXiv](https://img.shields.io/badge/arXiv-2602.02223-b31b1b?logo=arxiv)](https://arxiv.org/abs/2602.02223) |
| Active Noise Cancellation on Open-Ear Smart Glasses | [![arXiv](https://img.shields.io/badge/arXiv-2604.05519-b31b1b?logo=arxiv)](https://arxiv.org/abs/2604.05519) |
| Urban Risk-Aware Navigation via VQA-Based Event Maps for People with Low Vision | [![arXiv](https://img.shields.io/badge/arXiv-2605.11782-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.11782) |

### 4.3 Industrial Workflow Support

| Paper Title | Link |
|---|---|
| COIN: A Large-Scale Dataset for Comprehensive Instructional Video Analysis | [![arXiv](https://img.shields.io/badge/arXiv-1903.02874-b31b1b?logo=arxiv)](https://arxiv.org/abs/1903.02874) |
| Smart Glasses-Based Personnel Proximity Warning System for Improving Pedestrian Safety in Construction and Mining Sites | [![MDPI](https://img.shields.io/badge/MDPI-Link-0085ca?style=flat-square)](https://www.mdpi.com/1660-4601/17/4/1422) |
| Augmented Reality’s Impact in Industry—A Scoping Review | [![MDPI](https://img.shields.io/badge/MDPI-Link-0085ca?style=flat-square)](https://www.mdpi.com/2076-3417/15/5/2415) |
| The IKEA ASM Dataset: Understanding People Assembling Furniture through Actions, Objects and Pose | [![arXiv](https://img.shields.io/badge/arXiv-2007.00394-b31b1b?logo=arxiv)](https://arxiv.org/abs/2007.00394) |
| Augmented Reality Smart Glasses in Industrial Assembly: Current Status and Future Challenges | [![ScienceDirect](https://img.shields.io/badge/ScienceDirect-Link-0085ca?style=flat-square)](https://www.sciencedirect.com/science/article/abs/pii/S2452414X20300509) |
| Assembly101: A Large-Scale Multi-View Video Dataset for Understanding Procedural Activities | [![arXiv](https://img.shields.io/badge/arXiv-2203.14712-b31b1b?logo=arxiv)](https://arxiv.org/abs/2203.14712) |
| HoloAssist: An Egocentric Human Interaction Dataset for Interactive AI Assistants in the Real World | [![arXiv](https://img.shields.io/badge/arXiv-2309.17024-b31b1b?logo=arxiv)](https://arxiv.org/abs/2309.17024) |
| Head-Mounted Display Augmented Reality in Manufacturing: A Systematic Review | [![ACM DL](https://img.shields.io/badge/ACM%20DL-Link-0085ca?style=flat-square)](https://dl.acm.org/doi/10.1016/j.rcim.2023.102567) |
| LabOS: The AI-XR Co-scientist that sees and works with humans | [![arXiv](https://img.shields.io/badge/arXiv-2510.14861-b31b1b?logo=arxiv)](https://arxiv.org/abs/2510.14861) |
| Pro $^2$ Assist: Continuous Step-Aware Proactive Assistance with Multimodal Egocentric Perception for Long-Horizon Procedural Tasks | [![arXiv](https://img.shields.io/badge/arXiv-2605.04227-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.04227) |
| Plan, Watch, Recover: A Benchmark and Architectures for Proactive Procedural Assistance | [![arXiv](https://img.shields.io/badge/arXiv-2606.04970-b31b1b?logo=arxiv)](https://arxiv.org/abs/2606.04970) |
| Streaming Interventions: Can Video Large Language Models Correct Mistakes as They Occur? | [![arXiv](https://img.shields.io/badge/arXiv-2606.09547-b31b1b?logo=arxiv)](https://arxiv.org/abs/2606.09547) |
| Toward a Full-Stack Framework for Industrial Augmented Reality: Benefits, Risks, and Design Considerations for Dependable Deployment in Manufacturing | [![arXiv](https://img.shields.io/badge/arXiv-2606.11112-b31b1b?logo=arxiv)](https://arxiv.org/abs/2606.11112) |

### 4.4 Healthcare and Caregiving

| Paper Title | Link |
|---|---|
| JHU-ISI Gesture and Skill Assessment Working Set (JIGSAWS): A Surgical Activity Dataset for Human Motion Modeling | [![CIRL](https://img.shields.io/badge/CIRL-Link-0085ca?style=flat-square)](https://cirl.lcsr.jhu.edu/research/hmm/datasets/jigsaws_release/) |
| Technical Support by Smart Glasses During a Mass Casualty Incident | [![PubMed](https://img.shields.io/badge/PubMed-Link-0085ca?style=flat-square)](https://pubmed.ncbi.nlm.nih.gov/30609988/) |
| A Systematic Literature Review on Integrating AI-Powered Smart Glasses into Digital Health Management for Proactive Healthcare Solutions | [![Nature](https://img.shields.io/badge/Nature-Link-0085ca?style=flat-square)](https://www.nature.com/articles/s41746-025-01715-x) |
| Development of an AI-Powered AR Glasses System for Real-Time First Aid Guidance in Emergency Situations | [![Springer Nature](https://img.shields.io/badge/Springer%20Nature-Link-1f77b4?style=flat-square)](https://link.springer.com/article/10.1186/s13040-025-00473-6) |
| Smart Glasses for Older Adults With Cognitive Impairment: A Scoping Review | [![PubMed Central](https://img.shields.io/badge/PubMed%20Central-Link-0085ca?style=flat-square)](https://pmc.ncbi.nlm.nih.gov/articles/PMC12633631/) |
| A Smart-Glasses for Emergency Medical Services via Multimodal Multitask Learning | [![arXiv](https://img.shields.io/badge/arXiv-2511.13078-b31b1b?logo=arxiv)](https://arxiv.org/abs/2511.13078) |
| Wearable AR for Restorative Breaks: How Interactive Narrative Experiences Support Relaxation for Young People | [![arXiv](https://img.shields.io/badge/arXiv-2602.16323-b31b1b?logo=arxiv)](https://arxiv.org/abs/2602.16323) |

### 4.5 Education and Skills Training

| Paper Title | Link |
|---|---|
| Cross-Task Weakly Supervised Learning from Instructional Videos | [![arXiv](https://img.shields.io/badge/arXiv-1903.08225-b31b1b?logo=arxiv)](https://arxiv.org/abs/1903.08225) |
| Evaluating the Effectiveness of Learning Design with Mixed Reality in Higher Education | [![Springer Nature](https://img.shields.io/badge/Springer%20Nature-Link-1f77b4?style=flat-square)](https://link.springer.com/article/10.1007/s10055-020-00427-9) |
| Augmented Reality in Medical Education: A Systematic Review | [![PubMed Central](https://img.shields.io/badge/PubMed%20Central-Link-0085ca?style=flat-square)](https://pmc.ncbi.nlm.nih.gov/articles/PMC7082471/) |
| Rescaling Egocentric Vision: Collection, Pipeline and Challenges for EPIC-KITCHENS-100 | [![arXiv](https://img.shields.io/badge/arXiv-2006.13256-b31b1b?logo=arxiv)](https://arxiv.org/abs/2006.13256) |
| A Critical Evaluation, Challenges, and Future Perspectives of Using AI and Emerging Technologies in Smart Classrooms | [![Springer Nature](https://img.shields.io/badge/Springer%20Nature-Link-1f77b4?style=flat-square)](https://link.springer.com/article/10.1186/s40561-023-00231-3) |
| The Use of Smart Glasses in Nursing Education: A Scoping Review | [![PubMed](https://img.shields.io/badge/PubMed-Link-0085ca?style=flat-square)](https://pubmed.ncbi.nlm.nih.gov/37924651/) |
| Evaluating the Feasibility of Augmented Reality to Support Communication Access for Deaf Students in Experiential Higher Education Contexts | [![arXiv](https://img.shields.io/badge/arXiv-2604.00856-b31b1b?logo=arxiv)](https://arxiv.org/abs/2604.00856) |

### 4.6 Mobility and Transportation Safety

| Paper Title | Link |
|---|---|
| NavCog: A Navigational Cognitive Assistant for the Blind | [![ACM DL](https://img.shields.io/badge/ACM%20DL-Link-0085ca?style=flat-square)](https://dl.acm.org/doi/10.1145/2935334.2935361) |
| Are They Going to Cross? A Benchmark Dataset and Baseline for Pedestrian Crosswalk Behavior | [![IEEE](https://img.shields.io/badge/IEEE-Link-0085ca?style=flat-square)](https://www.computer.org/csdl/proceedings-article/iccvw/2017/1034a206/12OmNBiygvp) |
| PIE: A Large-Scale Dataset and Models for Pedestrian Intention Estimation and Trajectory Prediction | [![ResearchGate](https://img.shields.io/badge/ResearchGate-Link-0085ca?style=flat-square)](https://www.researchgate.net/publication/339558368_PIE_A_Large-Scale_Dataset_and_Models_for_Pedestrian_Intention_Estimation_and_Trajectory_Prediction) |
| The Effectiveness of Visual and Audio Wayfinding Guidance on Smartglasses for People with Low Vision | [![ACM DL](https://img.shields.io/badge/ACM%20DL-Link-0085ca?style=flat-square)](https://dl.acm.org/doi/10.1145/3313831.3376516) |
| Urban Risk-Aware Navigation via VQA-Based Event Maps for People with Low Vision | [![arXiv](https://img.shields.io/badge/arXiv-2605.11782-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.11782) |
| Decoding Pedestrian Crossing Intention from Egocentric Vision via Vision Language Models | [![arXiv](https://img.shields.io/badge/arXiv-2606.09142-b31b1b?logo=arxiv)](https://arxiv.org/abs/2606.09142) |

### 4.7 Social Interaction and Collaboration

| Paper Title | Link |
|---|---|
| The AMI Meeting Corpus: A Pre-Announcement | [![Springer Nature](https://img.shields.io/badge/Springer%20Nature-Link-1f77b4?style=flat-square)](https://link.springer.com/chapter/10.1007/11677482_3) |
| In Situ with Bystanders of Augmented Reality Glasses: Perspectives on Recording and Privacy-Mediating Technologies | [![ACM DL](https://img.shields.io/badge/ACM%20DL-Link-0085ca?style=flat-square)](https://dl.acm.org/doi/10.1145/2556288.2557352) |
| Your Smart Glasses' Camera Bothers Me! Exploring Opt-In and Opt-Out Gestures for Privacy Mediation | [![ACM DL](https://img.shields.io/badge/ACM%20DL-Link-0085ca?style=flat-square)](https://dl.acm.org/doi/10.1145/3240167.3240174) |
| AVA Active Speaker: An Audio-Visual Dataset for Active Speaker Detection | [![arXiv](https://img.shields.io/badge/arXiv-1901.01342-b31b1b?logo=arxiv)](https://arxiv.org/abs/1901.01342) |
| Evaluating a Wearable Camera's Social Acceptability In-the-Wild | [![ACM DL](https://img.shields.io/badge/ACM%20DL-Link-0085ca?style=flat-square)](https://dl.acm.org/doi/10.1145/3290607.3312837) |
| QMSum: A New Benchmark for Query-Based Multi-Domain Meeting Summarization | [![arXiv](https://img.shields.io/badge/arXiv-2104.05938-b31b1b?logo=arxiv)](https://arxiv.org/abs/2104.05938) |
| Social Acceptance of Smart Glasses in Health Care: Model Evaluation Study of Anticipated Adoption and Social Interaction | [![PubMed Central](https://img.shields.io/badge/PubMed%20Central-Link-0085ca?style=flat-square)](https://pmc.ncbi.nlm.nih.gov/articles/PMC11862762/) |
| VisGuardian: A Lightweight Group-based Privacy Control Technique For Front Camera Data From AR Glasses in Home Environments | [![arXiv](https://img.shields.io/badge/arXiv-2601.19502-b31b1b?logo=arxiv)](https://arxiv.org/abs/2601.19502) |
| Conversational Successes and Breakdowns in Everyday Smart Glasses Use | [![arXiv](https://img.shields.io/badge/arXiv-2602.22340-b31b1b?logo=arxiv)](https://arxiv.org/abs/2602.22340) |
| Mind the Gap: Mapping Wearer--Bystander Privacy Tensions and Context-Adaptive Pathways for Camera Glasses | [![arXiv](https://img.shields.io/badge/arXiv-2603.04930-b31b1b?logo=arxiv)](https://arxiv.org/abs/2603.04930) |
| Reshaping Inclusive Interpersonal Dynamics through Smart Glasses in Mixed-Vision Social Activities | [![arXiv](https://img.shields.io/badge/arXiv-2604.07232-b31b1b?logo=arxiv)](https://arxiv.org/abs/2604.07232) |
| Position: Life-Logging Video Streams Make the Privacy-Utility Trade-off Inevitable | [![arXiv](https://img.shields.io/badge/arXiv-2605.10404-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.10404) |
| H2HMem: A Multimodal Memory Benchmark for Agents in Human-Human Interactions | [![arXiv](https://img.shields.io/badge/arXiv-2606.09461-b31b1b?logo=arxiv)](https://arxiv.org/abs/2606.09461) |

### 4.8 Spatial Intelligence

| Paper Title | Link |
|---|---|
| VINS-Mono: A Robust and Versatile Monocular Visual-Inertial State Estimator | [![arXiv](https://img.shields.io/badge/arXiv-1708.03852-b31b1b?logo=arxiv)](https://arxiv.org/abs/1708.03852) |
| Matterport3D: Learning from RGB-D Data in Indoor Environments | [![arXiv](https://img.shields.io/badge/arXiv-1709.06158-b31b1b?logo=arxiv)](https://arxiv.org/abs/1709.06158) |
| In the Eye of the Beholder: Joint Learning of Gaze and Actions in First Person Video | [![arXiv](https://img.shields.io/badge/arXiv-2006.00626-b31b1b?logo=arxiv)](https://arxiv.org/abs/2006.00626) |
| ORB-SLAM3: An Accurate Open-Source Library for Visual, Visual-Inertial, and Multimap SLAM | [![arXiv](https://img.shields.io/badge/arXiv-2007.11898-b31b1b?logo=arxiv)](https://arxiv.org/abs/2007.11898) |
| DROID-SLAM: Deep Visual SLAM for Monocular, Stereo, and RGB-D Cameras | [![arXiv](https://img.shields.io/badge/arXiv-2108.10869-b31b1b?logo=arxiv)](https://arxiv.org/abs/2108.10869) |
| Aria Digital Twin: A New Benchmark Dataset for Egocentric 3D Machine Perception | [![arXiv](https://img.shields.io/badge/arXiv-2306.06362-b31b1b?logo=arxiv)](https://arxiv.org/abs/2306.06362) |
| Project Aria: A New Tool for Egocentric Multi-Modal AI Research | [![arXiv](https://img.shields.io/badge/arXiv-2308.13561-b31b1b?logo=arxiv)](https://arxiv.org/abs/2308.13561) |
| LEVIO: Lightweight Embedded Visual Inertial Odometry for Resource-Constrained Devices | [![arXiv](https://img.shields.io/badge/arXiv-2602.03294-b31b1b?logo=arxiv)](https://arxiv.org/abs/2602.03294) |
| EgoForge: Goal-Directed Egocentric World Simulator | [![arXiv](https://img.shields.io/badge/arXiv-2603.20169-b31b1b?logo=arxiv)](https://arxiv.org/abs/2603.20169) |
| Pandora: Articulated 3D Scene Graphs from Egocentric Vision | [![arXiv](https://img.shields.io/badge/arXiv-2603.28732-b31b1b?logo=arxiv)](https://arxiv.org/abs/2603.28732) |
| Do MLLMs Understand Pointing? Benchmarking and Enhancing Referential Reasoning in Egocentric Vision | [![arXiv](https://img.shields.io/badge/arXiv-2604.21461-b31b1b?logo=arxiv)](https://arxiv.org/abs/2604.21461) |
| EgoProx: Evaluating MLLMs on Egocentric 3D Proximity Reasoning Across a Cognitive Hierarchy | [![arXiv](https://img.shields.io/badge/arXiv-2605.24456-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.24456) |
| SpatialWorld: Benchmarking Interactive Spatial Reasoning of Multimodal Agents in Real-World Tasks | [![arXiv](https://img.shields.io/badge/arXiv-2606.09669-b31b1b?logo=arxiv)](https://arxiv.org/abs/2606.09669) |

### 4.9 Embodied Intelligence

| Paper Title | Link |
|---|---|
| Ego4D: Around the World in 3,000 Hours of Egocentric Video | [![arXiv](https://img.shields.io/badge/arXiv-2110.07058-b31b1b?logo=arxiv)](https://arxiv.org/abs/2110.07058) |
| Ego-Exo4D: Understanding Skilled Human Activity from First- and Third-Person Perspectives | [![arXiv](https://img.shields.io/badge/arXiv-2311.18259-b31b1b?logo=arxiv)](https://arxiv.org/abs/2311.18259) |
| EgoMimic: Scaling Imitation Learning via Egocentric Video | [![arXiv](https://img.shields.io/badge/arXiv-2410.24221-b31b1b?logo=arxiv)](https://arxiv.org/abs/2410.24221) |
| EgoDex: Learning Dexterous Manipulation from Large-Scale Egocentric Video | [![arXiv](https://img.shields.io/badge/arXiv-2505.11709-b31b1b?logo=arxiv)](https://arxiv.org/abs/2505.11709) |
| EgoZero: Robot Learning from Smart Glasses | [![arXiv](https://img.shields.io/badge/arXiv-2505.20290-b31b1b?logo=arxiv)](https://arxiv.org/abs/2505.20290) |
| EgoVLA: Learning Vision-Language-Action Models from Egocentric Human Videos | [![arXiv](https://img.shields.io/badge/arXiv-2507.12440-b31b1b?logo=arxiv)](https://arxiv.org/abs/2507.12440) |
| EgoBridge: Domain Adaptation for Generalizable Imitation from Egocentric Human Data | [![arXiv](https://img.shields.io/badge/arXiv-2509.19626-b31b1b?logo=arxiv)](https://arxiv.org/abs/2509.19626) |
| Scalable Vision-Language-Action Model Pretraining for Robotic Manipulation with Real-Life Human Activity Videos | [![arXiv](https://img.shields.io/badge/arXiv-2510.21571-b31b1b?logo=arxiv)](https://arxiv.org/abs/2510.21571) |
| EgoMI: Learning Active Vision and Whole-Body Manipulation from Egocentric Human Demonstrations | [![arXiv](https://img.shields.io/badge/arXiv-2511.00153-b31b1b?logo=arxiv)](https://arxiv.org/abs/2511.00153) |
| EgoScale: Scaling Dexterous Manipulation with Diverse Egocentric Human Data | [![arXiv](https://img.shields.io/badge/arXiv-2602.16710-b31b1b?logo=arxiv)](https://arxiv.org/abs/2602.16710) |
| AoE: Always-On Egocentric Human Video Collection for Embodied AI | [![arXiv](https://img.shields.io/badge/arXiv-2602.23893-b31b1b?logo=arxiv)](https://arxiv.org/abs/2602.23893) |
| UniDex: A Robot Foundation Suite for Universal Dexterous Hand Control from Egocentric Human Videos | [![arXiv](https://img.shields.io/badge/arXiv-2603.22264-b31b1b?logo=arxiv)](https://arxiv.org/abs/2603.22264) |
| ActiveGlasses: Learning Manipulation with Active Vision from Ego-Centric Human Demonstration | [![arXiv](https://img.shields.io/badge/arXiv-2604.08534-b31b1b?logo=arxiv)](https://arxiv.org/abs/2604.08534) |
| HumanNet: Scaling Human-Centric Video Learning to One Million Hours | [![arXiv](https://img.shields.io/badge/arXiv-2605.06747-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.06747) |
| EgoKit: Towards Unified Low-Cost Egocentric Data Collection with Heterogeneous Devices | [![arXiv](https://img.shields.io/badge/arXiv-2605.16797-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.16797) |
| HumanEgo: Zero-Shot Robot Learning from Minutes of Human Egocentric Videos | [![arXiv](https://img.shields.io/badge/arXiv-2605.24934-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.24934) |
| ActiveMimic: Egocentric Video Pretraining with Active Perception | [![arXiv](https://img.shields.io/badge/arXiv-2606.06194-b31b1b?logo=arxiv)](https://arxiv.org/abs/2606.06194) |
| EgoTactile: Learning Grasp Pressure for Everyday Objects from Egocentric Video | [![arXiv](https://img.shields.io/badge/arXiv-2606.09243-b31b1b?logo=arxiv)](https://arxiv.org/abs/2606.09243) |
| EgoEngine: From Egocentric Human Videos to High-Fidelity Dexterous Robot Demonstrations | [![arXiv](https://img.shields.io/badge/arXiv-2606.12604-b31b1b?logo=arxiv)](https://arxiv.org/abs/2606.12604) |
| EPIC: A System Framework for Efficient Egocentric Perception on Embodied AR Glasses | [![arXiv](https://img.shields.io/badge/arXiv-2606.15859-b31b1b?logo=arxiv)](https://arxiv.org/abs/2606.15859) |
| Human Universal Grasping | [![arXiv](https://img.shields.io/badge/arXiv-2606.17054-b31b1b?logo=arxiv)](https://arxiv.org/abs/2606.17054) |
| ForceBand: Learning Forceful Manipulation with sEMG | [![arXiv](https://img.shields.io/badge/arXiv-2606.26093-b31b1b?logo=arxiv)](https://arxiv.org/abs/2606.26093) |
| EgoWAM: World Action Models Beyond Pixels with In-the-Wild Egocentric Human Data | [![arXiv](https://img.shields.io/badge/arXiv-2607.08436-b31b1b?logo=arxiv)](https://arxiv.org/abs/2607.08436) |
| Open-AoE: An Open Egocentric Manipulation Dataset and Toolchain for Embodied Learning | [![arXiv](https://img.shields.io/badge/arXiv-2607.14183-b31b1b?logo=arxiv)](https://arxiv.org/abs/2607.14183) |
| EgoExoMoCap: Distributed Ego-Exo Human Motion Capture | [![arXiv](https://img.shields.io/badge/arXiv-2607.15868-b31b1b?logo=arxiv)](https://arxiv.org/abs/2607.15868) |

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
