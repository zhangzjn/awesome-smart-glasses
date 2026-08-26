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

> The table of representative smart-glasses products/platforms would be updated soon.

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

> ⏰ In chronological order, from the earliest to the latest.
> 🎨 Colored labels indicate the foundational capabilities to which the work contributes.

| Capabilities | Paper Title | Link |
|---|---|---|
| <span style="background-color:#7c3aed;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Multimodal Context Modeling</span> | The AMI Meeting Corpus: A Pre-Announcement | - |
| <span style="background-color:#475569;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Cross-Cutting Deployment Constraints</span> | In Situ with Bystanders of Augmented Reality Glasses: Perspectives on Recording and Privacy-Mediating Technologies | - |
| <span style="background-color:#059669;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Persistent Spatial State</span> | NavCog: A Navigational Cognitive Assistant for the Blind | - |
| <span style="background-color:#059669;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Persistent Spatial State</span> | Matterport3D: Learning from RGB-D Data in Indoor Environments | [![arXiv](https://img.shields.io/badge/arXiv-1709.06158-b31b1b?logo=arxiv)](https://arxiv.org/abs/1709.06158) |
| <span style="background-color:#059669;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Persistent Spatial State</span> | ScanNet: Richly-Annotated 3D Reconstructions of Indoor Scenes | [![arXiv](https://img.shields.io/badge/arXiv-1703.08805-b31b1b?logo=arxiv)](https://arxiv.org/abs/1703.08805) |
| <span style="background-color:#475569;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Cross-Cutting Deployment Constraints</span> | Your Smart Glasses' Camera Bothers Me! Exploring Opt-In and Opt-Out Gestures for Privacy Mediation | - |
| <span style="background-color:#059669;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Persistent Spatial State</span> | Vision-and-Language Navigation: Interpreting Visually-Grounded Navigation Instructions in Real Environments | [![arXiv](https://img.shields.io/badge/arXiv-1711.07280-b31b1b?logo=arxiv)](https://arxiv.org/abs/1711.07280) |
| <span style="background-color:#059669;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Persistent Spatial State</span> | VINS-Mono: A Robust and Versatile Monocular Visual-Inertial State Estimator | [![arXiv](https://img.shields.io/badge/arXiv-1708.03852-b31b1b?logo=arxiv)](https://arxiv.org/abs/1708.03852) |
| <span style="background-color:#2563eb;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">First-Person Perception</span><br><span style="background-color:#059669;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Persistent Spatial State</span> | VizWiz Grand Challenge: Answering Visual Questions from Blind People | [![arXiv](https://img.shields.io/badge/arXiv-1802.08218-b31b1b?logo=arxiv)](https://arxiv.org/abs/1802.08218) |
| <span style="background-color:#2563eb;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">First-Person Perception</span><br><span style="background-color:#059669;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Persistent Spatial State</span> | In the Eye of the Beholder: Joint Learning of Gaze and Actions in First Person Video | - |
| <span style="background-color:#0f766e;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Embodied Data Interfaces</span> | COIN: A Large-Scale Dataset for Comprehensive Instructional Video Analysis | [![arXiv](https://img.shields.io/badge/arXiv-1903.02874-b31b1b?logo=arxiv)](https://arxiv.org/abs/1903.02874) |
| <span style="background-color:#0f766e;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Embodied Data Interfaces</span> | Cross-Task Weakly Supervised Learning from Instructional Videos | [![arXiv](https://img.shields.io/badge/arXiv-1903.08272-b31b1b?logo=arxiv)](https://arxiv.org/abs/1903.08272) |
| <span style="background-color:#475569;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Cross-Cutting Deployment Constraints</span> | Evaluating a Wearable Camera's Social Acceptability In-the-Wild | - |
| <span style="background-color:#7c3aed;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Multimodal Context Modeling</span> | AVA Active Speaker: An Audio-Visual Dataset for Active Speaker Detection | [![arXiv](https://img.shields.io/badge/arXiv-1901.01342-b31b1b?logo=arxiv)](https://arxiv.org/abs/1901.01342) |
| <span style="background-color:#059669;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Persistent Spatial State</span> | REVERIE: Remote Embodied Visual Referring Expression in Real Indoor Environments | [![arXiv](https://img.shields.io/badge/arXiv-1904.02716-b31b1b?logo=arxiv)](https://arxiv.org/abs/1904.02716) |
| <span style="background-color:#059669;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Persistent Spatial State</span> | DROID-SLAM: Deep Visual SLAM for Monocular, Stereo, and RGB-D Cameras | [![arXiv](https://img.shields.io/badge/arXiv-2108.10869-b31b1b?logo=arxiv)](https://arxiv.org/abs/2108.10869) |
| <span style="background-color:#0f766e;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Embodied Data Interfaces</span> | The IKEA ASM Dataset: Understanding People Assembling Furniture through Actions, Objects and Pose | - |
| <span style="background-color:#059669;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Persistent Spatial State</span> | ORB-SLAM3: An Accurate Open-Source Library for Visual, Visual-Inertial, and Multimap SLAM | [![arXiv](https://img.shields.io/badge/arXiv-2007.11898-b31b1b?logo=arxiv)](https://arxiv.org/abs/2007.11898) |
| <span style="background-color:#7c3aed;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Multimodal Context Modeling</span> | QMSum: A New Benchmark for Query-Based Multi-Domain Meeting Summarization | [![arXiv](https://img.shields.io/badge/arXiv-2104.05972-b31b1b?logo=arxiv)](https://arxiv.org/abs/2104.05972) |
| <span style="background-color:#7c3aed;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Multimodal Context Modeling</span><br><span style="background-color:#0f766e;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Embodied Data Interfaces</span> | Assembly101: A Large-Scale Multi-View Video Dataset for Understanding Procedural Activities | [![arXiv](https://img.shields.io/badge/arXiv-2203.14700-b31b1b?logo=arxiv)](https://arxiv.org/abs/2203.14700) |
| <span style="background-color:#2563eb;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">First-Person Perception</span> | Rescaling Egocentric Vision: Collection, Pipeline and Challenges for EPIC-KITCHENS-100 | [![arXiv](https://img.shields.io/badge/arXiv-2006.13256-b31b1b?logo=arxiv)](https://arxiv.org/abs/2006.13256) |
| <span style="background-color:#2563eb;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">First-Person Perception</span> | Ego4D: Around the World in 3,000 Hours of Egocentric Video | [![arXiv](https://img.shields.io/badge/arXiv-2110.07058-b31b1b?logo=arxiv)](https://arxiv.org/abs/2110.07058) |
| <span style="background-color:#059669;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Persistent Spatial State</span> | LidSonic for Visually Impaired: Green Machine Learning-Based Assistive Smart Glasses with Smart App and Arduino | - |
| <span style="background-color:#0f766e;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Embodied Data Interfaces</span> | R3M: A Universal Visual Representation for Robot Manipulation | [![arXiv](https://img.shields.io/badge/arXiv-2203.12601-b31b1b?logo=arxiv)](https://arxiv.org/abs/2203.12601) |
| <span style="background-color:#dc2626;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Situated Agentic Action</span><br><span style="background-color:#0f766e;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Embodied Data Interfaces</span> | RT-1: Robotics Transformer for Real-World Control at Scale | [![arXiv](https://img.shields.io/badge/arXiv-2212.06817-b31b1b?logo=arxiv)](https://arxiv.org/abs/2212.06817) |
| <span style="background-color:#dc2626;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Situated Agentic Action</span><br><span style="background-color:#0f766e;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Embodied Data Interfaces</span> | Do As I Can, Not As I Say: Grounding Language in Robotic Affordances | [![arXiv](https://img.shields.io/badge/arXiv-2204.01691-b31b1b?logo=arxiv)](https://arxiv.org/abs/2204.01691) |
| <span style="background-color:#475569;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Cross-Cutting Deployment Constraints</span> | Head-Mounted Display Augmented Reality in Manufacturing: A Systematic Review | - |
| <span style="background-color:#059669;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Persistent Spatial State</span><br><span style="background-color:#0f766e;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Embodied Data Interfaces</span> | Aria Digital Twin: A New Benchmark Dataset for Egocentric 3D Machine Perception | - |
| <span style="background-color:#0f766e;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Embodied Data Interfaces</span> | BridgeData V2: A Dataset for Robot Learning at Scale | [![arXiv](https://img.shields.io/badge/arXiv-2308.12952-b31b1b?logo=arxiv)](https://arxiv.org/abs/2308.12952) |
| <span style="background-color:#2563eb;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">First-Person Perception</span> | EgoObjects: A Large-Scale Egocentric Dataset for Fine-Grained Object Understanding | - |
| <span style="background-color:#2563eb;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">First-Person Perception</span><br><span style="background-color:#d97706;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Auditable Long-Term Personal Memory</span> | EgoTracks: A Long-Term Egocentric Visual Object Tracking Dataset | - |
| <span style="background-color:#7c3aed;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Multimodal Context Modeling</span> | EgoVLPv2: Egocentric Video-Language Pre-Training with Fusion in the Backbone | - |
| <span style="background-color:#2563eb;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">First-Person Perception</span><br><span style="background-color:#7c3aed;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Multimodal Context Modeling</span><br><span style="background-color:#dc2626;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Situated Agentic Action</span><br><span style="background-color:#0f766e;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Embodied Data Interfaces</span> | HoloAssist: An Egocentric Human Interaction Dataset for Interactive AI Assistants in the Real World | - |
| <span style="background-color:#2563eb;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">First-Person Perception</span><br><span style="background-color:#7c3aed;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Multimodal Context Modeling</span><br><span style="background-color:#059669;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Persistent Spatial State</span><br><span style="background-color:#0f766e;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Embodied Data Interfaces</span><br><span style="background-color:#475569;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Cross-Cutting Deployment Constraints</span> | Project Aria: A New Tool for Egocentric Multi-Modal AI Research | [![arXiv](https://img.shields.io/badge/arXiv-2308.13561-b31b1b?logo=arxiv)](https://arxiv.org/abs/2308.13561) |
| <span style="background-color:#475569;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Cross-Cutting Deployment Constraints</span> | Rethinking Mobile Block for Efficient Attention-Based Models | - |
| <span style="background-color:#0f766e;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Embodied Data Interfaces</span><br><span style="background-color:#475569;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Cross-Cutting Deployment Constraints</span> | DROID: A Large-Scale In-the-Wild Robot Manipulation Dataset | [![arXiv](https://img.shields.io/badge/arXiv-2403.12945-b31b1b?logo=arxiv)](https://arxiv.org/abs/2403.12945) |
| <span style="background-color:#0f766e;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Embodied Data Interfaces</span><br><span style="background-color:#475569;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Cross-Cutting Deployment Constraints</span> | Ego-Exo4D: Understanding Skilled Human Activity from First- and Third-Person Perspectives | [![arXiv](https://img.shields.io/badge/arXiv-2311.18259-b31b1b?logo=arxiv)](https://arxiv.org/abs/2311.18259) |
| <span style="background-color:#d97706;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Auditable Long-Term Personal Memory</span> | Memoro: Using Large Language Models to Realize a Concise Interface for Real-Time Memory Augmentation | - |
| <span style="background-color:#dc2626;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Situated Agentic Action</span> | Mobile-Agent: Autonomous Multi-Modal Mobile Device Agent with Visual Perception | [![arXiv](https://img.shields.io/badge/arXiv-2401.16158-b31b1b?logo=arxiv)](https://arxiv.org/abs/2401.16158) |
| <span style="background-color:#0f766e;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Embodied Data Interfaces</span><br><span style="background-color:#475569;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Cross-Cutting Deployment Constraints</span> | Open X-Embodiment: Robotic Learning Datasets and RT-X Models: Open X-Embodiment Collaboration 0 | [![arXiv](https://img.shields.io/badge/arXiv-2310.08864-b31b1b?logo=arxiv)](https://arxiv.org/abs/2310.08864) |
| <span style="background-color:#7c3aed;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Multimodal Context Modeling</span><br><span style="background-color:#059669;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Persistent Spatial State</span><br><span style="background-color:#d97706;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Auditable Long-Term Personal Memory</span> | OpenEQA: Embodied Question Answering in the Era of Foundation Models | - |
| <span style="background-color:#dc2626;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Situated Agentic Action</span> | GPT-4V(ision) is a Generalist Web Agent, if Grounded | [![arXiv](https://img.shields.io/badge/arXiv-2401.01614-b31b1b?logo=arxiv)](https://arxiv.org/abs/2401.01614) |
| <span style="background-color:#dc2626;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Situated Agentic Action</span><br><span style="background-color:#475569;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Cross-Cutting Deployment Constraints</span> | Visual Adversarial Examples Jailbreak Aligned Large Language Models | - |
| <span style="background-color:#dc2626;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Situated Agentic Action</span> | WebArena: A Realistic Web Environment for Building Autonomous Agents | [![arXiv](https://img.shields.io/badge/arXiv-2307.13854-b31b1b?logo=arxiv)](https://arxiv.org/abs/2307.13854) |
| <span style="background-color:#dc2626;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Situated Agentic Action</span> | AI for Service: Proactive Assistance with AI Glasses | [![arXiv](https://img.shields.io/badge/arXiv-2510.14359-b31b1b?logo=arxiv)](https://arxiv.org/abs/2510.14359) |
| <span style="background-color:#0f766e;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Embodied Data Interfaces</span> | EgoMI: Learning Active Vision and Whole-Body Manipulation from Egocentric Human Demonstrations | [![arXiv](https://img.shields.io/badge/arXiv-2511.00153-b31b1b?logo=arxiv)](https://arxiv.org/abs/2511.00153) |
| <span style="background-color:#d97706;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Auditable Long-Term Personal Memory</span><br><span style="background-color:#475569;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Cross-Cutting Deployment Constraints</span> | EgoTrigger: Toward Audio-Driven Image Capture for Human Memory Enhancement in All-Day Energy-Efficient Smart Glasses | - |
| <span style="background-color:#0f766e;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Embodied Data Interfaces</span><br><span style="background-color:#475569;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Cross-Cutting Deployment Constraints</span> | EgoVLA: Learning Vision-Language-Action Models from Egocentric Human Videos | [![arXiv](https://img.shields.io/badge/arXiv-2507.12440-b31b1b?logo=arxiv)](https://arxiv.org/abs/2507.12440) |
| <span style="background-color:#7c3aed;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Multimodal Context Modeling</span><br><span style="background-color:#d97706;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Auditable Long-Term Personal Memory</span> | EgoLife: Towards Egocentric Life Assistant | - |
| <span style="background-color:#0f766e;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Embodied Data Interfaces</span> | EgoMimic: Scaling Imitation Learning via Egocentric Video | - |
| <span style="background-color:#0f766e;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Embodied Data Interfaces</span><br><span style="background-color:#475569;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Cross-Cutting Deployment Constraints</span> | EgoZero: Robot Learning from Smart Glasses | [![arXiv](https://img.shields.io/badge/arXiv-2505.20290-b31b1b?logo=arxiv)](https://arxiv.org/abs/2505.20290) |
| <span style="background-color:#7c3aed;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Multimodal Context Modeling</span> | EPIC-Sounds: A Large-Scale Dataset of Actions That Sound | - |
| <span style="background-color:#2563eb;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">First-Person Perception</span><br><span style="background-color:#059669;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Persistent Spatial State</span><br><span style="background-color:#0f766e;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Embodied Data Interfaces</span><br><span style="background-color:#475569;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Cross-Cutting Deployment Constraints</span> | LEVIO: Lightweight Embedded Visual Inertial Odometry for Resource-Constrained Devices | - |
| <span style="background-color:#7c3aed;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Multimodal Context Modeling</span> | AdaVideoRAG: Omni-Contextual Adaptive Retrieval-Augmented Efficient Long Video Understanding | - |
| <span style="background-color:#475569;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Cross-Cutting Deployment Constraints</span> | EMOv2: Pushing 5M Vision Model Frontier | - |
| <span style="background-color:#0f766e;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Embodied Data Interfaces</span> | ActiveMimic: Egocentric Video Pretraining with Active Perception | [![arXiv](https://img.shields.io/badge/arXiv-2606.06194-b31b1b?logo=arxiv)](https://arxiv.org/abs/2606.06194) |
| <span style="background-color:#7c3aed;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Multimodal Context Modeling</span><br><span style="background-color:#475569;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Cross-Cutting Deployment Constraints</span> | Active Noise Cancellation on Open-Ear Smart Glasses | [![arXiv](https://img.shields.io/badge/arXiv-2604.05519-b31b1b?logo=arxiv)](https://arxiv.org/abs/2604.05519) |
| <span style="background-color:#0f766e;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Embodied Data Interfaces</span> | ActiveGlasses: Learning Manipulation with Active Vision from Ego-Centric Human Demonstration | [![arXiv](https://img.shields.io/badge/arXiv-2604.08534-b31b1b?logo=arxiv)](https://arxiv.org/abs/2604.08534) |
| <span style="background-color:#7c3aed;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Multimodal Context Modeling</span><br><span style="background-color:#dc2626;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Situated Agentic Action</span> | Agentic Very Long Video Understanding | - |
| <span style="background-color:#2563eb;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">First-Person Perception</span><br><span style="background-color:#0f766e;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Embodied Data Interfaces</span> | AoE: Always-On Egocentric Human Video Collection for Embodied AI | [![arXiv](https://img.shields.io/badge/arXiv-2602.23893-b31b1b?logo=arxiv)](https://arxiv.org/abs/2602.23893) |
| <span style="background-color:#7c3aed;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Multimodal Context Modeling</span><br><span style="background-color:#dc2626;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Situated Agentic Action</span> | ContextAgent: Context-Aware Proactive LLM Agents with Open-World Sensory Perceptions | - |
| <span style="background-color:#7c3aed;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Multimodal Context Modeling</span><br><span style="background-color:#475569;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Cross-Cutting Deployment Constraints</span> | Conversational Successes and Breakdowns in Everyday Smart Glasses Use | [![arXiv](https://img.shields.io/badge/arXiv-2602.22340-b31b1b?logo=arxiv)](https://arxiv.org/abs/2602.22340) |
| <span style="background-color:#475569;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Cross-Cutting Deployment Constraints</span> | EPIC: A System Framework for Efficient Egocentric Perception on Embodied AR Glasses | [![arXiv](https://img.shields.io/badge/arXiv-2606.15859-b31b1b?logo=arxiv)](https://arxiv.org/abs/2606.15859) |
| <span style="background-color:#2563eb;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">First-Person Perception</span><br><span style="background-color:#0f766e;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Embodied Data Interfaces</span> | Ego-1K--A Large-Scale Multiview Video Dataset for Egocentric Vision | [![arXiv](https://img.shields.io/badge/arXiv-2603.13741-b31b1b?logo=arxiv)](https://arxiv.org/abs/2603.13741) |
| <span style="background-color:#dc2626;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Situated Agentic Action</span> | Ego-Grounding for Personalized Question-Answering in Egocentric Videos | [![arXiv](https://img.shields.io/badge/arXiv-2604.01966-b31b1b?logo=arxiv)](https://arxiv.org/abs/2604.01966) |
| <span style="background-color:#dc2626;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Situated Agentic Action</span> | Ego2Web: A Web Agent Benchmark Grounded in Egocentric Videos | [![arXiv](https://img.shields.io/badge/arXiv-2603.22529-b31b1b?logo=arxiv)](https://arxiv.org/abs/2603.22529) |
| <span style="background-color:#0f766e;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Embodied Data Interfaces</span> | EgoEngine: From Egocentric Human Videos to High-Fidelity Dexterous Robot Demonstrations | [![arXiv](https://img.shields.io/badge/arXiv-2606.12604-b31b1b?logo=arxiv)](https://arxiv.org/abs/2606.12604) |
| <span style="background-color:#7c3aed;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Multimodal Context Modeling</span><br><span style="background-color:#d97706;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Auditable Long-Term Personal Memory</span> | EgoExoMem: Cross-View Memory Reasoning over Synchronized Egocentric and Exocentric Videos | [![arXiv](https://img.shields.io/badge/arXiv-2605.18734-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.18734) |
| <span style="background-color:#0f766e;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Embodied Data Interfaces</span> | EgoExoMoCap: Distributed Ego-Exo Human Motion Capture | [![arXiv](https://img.shields.io/badge/arXiv-2607.15868-b31b1b?logo=arxiv)](https://arxiv.org/abs/2607.15868) |
| <span style="background-color:#059669;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Persistent Spatial State</span> | EgoForge: Goal-Directed Egocentric World Simulator | [![arXiv](https://img.shields.io/badge/arXiv-2603.20169-b31b1b?logo=arxiv)](https://arxiv.org/abs/2603.20169) |
| <span style="background-color:#2563eb;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">First-Person Perception</span><br><span style="background-color:#0f766e;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Embodied Data Interfaces</span><br><span style="background-color:#475569;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Cross-Cutting Deployment Constraints</span> | EgoKit: Towards Unified Low-Cost Egocentric Data Collection with Heterogeneous Devices | [![arXiv](https://img.shields.io/badge/arXiv-2605.16797-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.16797) |
| <span style="background-color:#7c3aed;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Multimodal Context Modeling</span><br><span style="background-color:#d97706;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Auditable Long-Term Personal Memory</span> | EgoMemReason: A Memory-Driven Reasoning Benchmark for Long-Horizon Egocentric Video Understanding | [![arXiv](https://img.shields.io/badge/arXiv-2605.09874-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.09874) |
| <span style="background-color:#d97706;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Auditable Long-Term Personal Memory</span> | EgoMonth: A Month-Level Egocentric Video Benchmark for Long-Term Spatiotemporal Memory | [![arXiv](https://img.shields.io/badge/arXiv-2608.13113-b31b1b?logo=arxiv)](https://arxiv.org/abs/2608.13113) |
| <span style="background-color:#dc2626;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Situated Agentic Action</span> | EgoPro-Bench: Benchmarking Personalized Proactive Interaction in Egocentric Video Streams | [![arXiv](https://img.shields.io/badge/arXiv-2605.07299-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.07299) |
| <span style="background-color:#059669;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Persistent Spatial State</span> | EgoProx: Evaluating MLLMs on Egocentric 3D Proximity Reasoning Across a Cognitive Hierarchy | [![arXiv](https://img.shields.io/badge/arXiv-2605.24456-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.24456) |
| <span style="background-color:#2563eb;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">First-Person Perception</span><br><span style="background-color:#7c3aed;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Multimodal Context Modeling</span><br><span style="background-color:#dc2626;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Situated Agentic Action</span><br><span style="background-color:#475569;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Cross-Cutting Deployment Constraints</span> | EgoSAT: A Comprehensive Benchmark of Egocentric Streaming Interaction Understanding | [![arXiv](https://img.shields.io/badge/arXiv-2606.24422-b31b1b?logo=arxiv)](https://arxiv.org/abs/2606.24422) |
| <span style="background-color:#7c3aed;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Multimodal Context Modeling</span><br><span style="background-color:#d97706;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Auditable Long-Term Personal Memory</span><br><span style="background-color:#475569;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Cross-Cutting Deployment Constraints</span> | EGOSTREAM: A Diagnostic Benchmark for Streaming Episodic Memory in Egocentric Vision | [![arXiv](https://img.shields.io/badge/arXiv-2605.31557-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.31557) |
| <span style="background-color:#2563eb;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">First-Person Perception</span><br><span style="background-color:#0f766e;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Embodied Data Interfaces</span> | EgoTactile: Learning Grasp Pressure for Everyday Objects from Egocentric Video | [![arXiv](https://img.shields.io/badge/arXiv-2606.09243-b31b1b?logo=arxiv)](https://arxiv.org/abs/2606.09243) |
| <span style="background-color:#dc2626;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Situated Agentic Action</span> | Egocentric Co-Pilot: Web-Native Smart-Glasses Agents for Assistive Egocentric AI | - |
| <span style="background-color:#0f766e;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Embodied Data Interfaces</span> | EgoDex: Learning Dexterous Manipulation from Large-Scale Egocentric Video | - |
| <span style="background-color:#7c3aed;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Multimodal Context Modeling</span><br><span style="background-color:#475569;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Cross-Cutting Deployment Constraints</span> | Evaluating the Feasibility of Augmented Reality to Support Communication Access for Deaf Students in Experiential Higher Education Contexts | - |
| <span style="background-color:#2563eb;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">First-Person Perception</span><br><span style="background-color:#475569;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Cross-Cutting Deployment Constraints</span> | Evaluating OCR Performance for Assistive Technology: Effects of Walking Speed, Camera Placement, and Camera Type | - |
| <span style="background-color:#2563eb;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">First-Person Perception</span><br><span style="background-color:#7c3aed;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Multimodal Context Modeling</span><br><span style="background-color:#475569;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Cross-Cutting Deployment Constraints</span> | GLIMPSE: Real-Time Text Recognition and Contextual Understanding for VQA in Wearables | [![arXiv](https://img.shields.io/badge/arXiv-2602.13479-b31b1b?logo=arxiv)](https://arxiv.org/abs/2602.13479) |
| <span style="background-color:#7c3aed;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Multimodal Context Modeling</span><br><span style="background-color:#d97706;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Auditable Long-Term Personal Memory</span> | H2HMem: A Multimodal Memory Benchmark for Agents in Human-Human Interactions | [![arXiv](https://img.shields.io/badge/arXiv-2606.09461-b31b1b?logo=arxiv)](https://arxiv.org/abs/2606.09461) |
| <span style="background-color:#0f766e;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Embodied Data Interfaces</span> | HumanEgo: Zero-Shot Robot Learning from Minutes of Human Egocentric Videos | [![arXiv](https://img.shields.io/badge/arXiv-2605.24934-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.24934) |
| <span style="background-color:#0f766e;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Embodied Data Interfaces</span> | HumanNet: Scaling Human-Centric Video Learning to One Million Hours | [![arXiv](https://img.shields.io/badge/arXiv-2605.06747-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.06747) |
| <span style="background-color:#7c3aed;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Multimodal Context Modeling</span><br><span style="background-color:#dc2626;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Situated Agentic Action</span><br><span style="background-color:#475569;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Cross-Cutting Deployment Constraints</span> | IPIBench: Evaluating Interactive Proactive Intelligence of MLLMs under Continuous Streams | [![arXiv](https://img.shields.io/badge/arXiv-2605.27074-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.27074) |
| <span style="background-color:#dc2626;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Situated Agentic Action</span> | Intention-Aware Semantic Agent Communications for AI Glasses | [![arXiv](https://img.shields.io/badge/arXiv-2604.23691-b31b1b?logo=arxiv)](https://arxiv.org/abs/2604.23691) |
| <span style="background-color:#059669;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Persistent Spatial State</span><br><span style="background-color:#d97706;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Auditable Long-Term Personal Memory</span> | Latent Spatial Memory for Video World Models | [![arXiv](https://img.shields.io/badge/arXiv-2606.09828-b31b1b?logo=arxiv)](https://arxiv.org/abs/2606.09828) |
| <span style="background-color:#d97706;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Auditable Long-Term Personal Memory</span> | LightMem-Ego: Your AI Memory for Everyday Life | [![arXiv](https://img.shields.io/badge/arXiv-2607.11487-b31b1b?logo=arxiv)](https://arxiv.org/abs/2607.11487) |
| <span style="background-color:#2563eb;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">First-Person Perception</span><br><span style="background-color:#059669;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Persistent Spatial State</span> | Do MLLMs Understand Pointing? Benchmarking and Enhancing Referential Reasoning in Egocentric Vision | - |
| <span style="background-color:#d97706;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Auditable Long-Term Personal Memory</span><br><span style="background-color:#475569;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Cross-Cutting Deployment Constraints</span> | Mind the Gap: Mapping Wearer--Bystander Privacy Tensions and Context-Adaptive Pathways for Camera Glasses | - |
| <span style="background-color:#d97706;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Auditable Long-Term Personal Memory</span><br><span style="background-color:#475569;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Cross-Cutting Deployment Constraints</span> | Exploring Multimodal LMMs for Online Episodic Memory Question Answering on the Edge | [![arXiv](https://img.shields.io/badge/arXiv-2602.22455-b31b1b?logo=arxiv)](https://arxiv.org/abs/2602.22455) |
| <span style="background-color:#2563eb;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">First-Person Perception</span><br><span style="background-color:#0f766e;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Embodied Data Interfaces</span><br><span style="background-color:#475569;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Cross-Cutting Deployment Constraints</span> | Open-AoE: An Open Egocentric Manipulation Dataset and Toolchain for Embodied Learning | [![arXiv](https://img.shields.io/badge/arXiv-2607.14183-b31b1b?logo=arxiv)](https://arxiv.org/abs/2607.14183) |
| <span style="background-color:#475569;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Cross-Cutting Deployment Constraints</span> | OpenGlass: A Sensing-Computing Split Architecture for Local MLLM-Driven Real-Time Visual Assistance | - |
| <span style="background-color:#475569;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Cross-Cutting Deployment Constraints</span> | OpenGlass: Ultra-Low-Power On-Device AI Eyewear with Event-Based Vision | [![arXiv](https://img.shields.io/badge/arXiv-2606.07431-b31b1b?logo=arxiv)](https://arxiv.org/abs/2606.07431) |
| <span style="background-color:#059669;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Persistent Spatial State</span> | Pandora: Articulated 3D Scene Graphs from Egocentric Vision | [![arXiv](https://img.shields.io/badge/arXiv-2603.28732-b31b1b?logo=arxiv)](https://arxiv.org/abs/2603.28732) |
| <span style="background-color:#7c3aed;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Multimodal Context Modeling</span><br><span style="background-color:#d97706;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Auditable Long-Term Personal Memory</span><br><span style="background-color:#dc2626;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Situated Agentic Action</span> | Personal Visual Context Learning in Large Multimodal Models | [![arXiv](https://img.shields.io/badge/arXiv-2605.10936-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.10936) |
| <span style="background-color:#dc2626;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Situated Agentic Action</span><br><span style="background-color:#475569;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Cross-Cutting Deployment Constraints</span> | PhySE: A Psychological Framework for Real-Time AR-LLM Social Engineering Attacks | [![arXiv](https://img.shields.io/badge/arXiv-2604.23148-b31b1b?logo=arxiv)](https://arxiv.org/abs/2604.23148) |
| <span style="background-color:#dc2626;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Situated Agentic Action</span><br><span style="background-color:#475569;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Cross-Cutting Deployment Constraints</span> | Plan, Watch, Recover: A Benchmark and Architectures for Proactive Procedural Assistance | [![arXiv](https://img.shields.io/badge/arXiv-2606.04970-b31b1b?logo=arxiv)](https://arxiv.org/abs/2606.04970) |
| <span style="background-color:#d97706;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Auditable Long-Term Personal Memory</span><br><span style="background-color:#475569;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Cross-Cutting Deployment Constraints</span> | Position: Life-Logging Video Streams Make the Privacy-Utility Trade-off Inevitable | [![arXiv](https://img.shields.io/badge/arXiv-2605.10404-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.10404) |
| <span style="background-color:#dc2626;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Situated Agentic Action</span> | Pro $^2$ Assist: Continuous Step-Aware Proactive Assistance with Multimodal Egocentric Perception for Long-Horizon Procedural Tasks | [![arXiv](https://img.shields.io/badge/arXiv-2605.04227-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.04227) |
| <span style="background-color:#7c3aed;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Multimodal Context Modeling</span> | Reshaping Inclusive Interpersonal Dynamics through Smart Glasses in Mixed-Vision Social Activities | - |
| <span style="background-color:#2563eb;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">First-Person Perception</span><br><span style="background-color:#7c3aed;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Multimodal Context Modeling</span><br><span style="background-color:#475569;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Cross-Cutting Deployment Constraints</span> | SAW-Bench: Learning Situated Awareness in the Real World | [![arXiv](https://img.shields.io/badge/arXiv-2602.16682-b31b1b?logo=arxiv)](https://arxiv.org/abs/2602.16682) |
| <span style="background-color:#059669;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Persistent Spatial State</span> | SpatialWorld: Benchmarking Interactive Spatial Reasoning of Multimodal Agents in Real-World Tasks | [![arXiv](https://img.shields.io/badge/arXiv-2606.09669-b31b1b?logo=arxiv)](https://arxiv.org/abs/2606.09669) |
| <span style="background-color:#dc2626;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Situated Agentic Action</span> | Streaming Interventions: Can Video Large Language Models Correct Mistakes as They Occur? | [![arXiv](https://img.shields.io/badge/arXiv-2606.09547-b31b1b?logo=arxiv)](https://arxiv.org/abs/2606.09547) |
| <span style="background-color:#2563eb;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">First-Person Perception</span><br><span style="background-color:#7c3aed;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Multimodal Context Modeling</span><br><span style="background-color:#475569;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Cross-Cutting Deployment Constraints</span> | SUPERGLASSES: Benchmarking Vision Language Models as Intelligent Agents for AI Smart Glasses | - |
| <span style="background-color:#475569;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Cross-Cutting Deployment Constraints</span> | UNSEEN: A Cross-Stack LLM Unlearning Defense against AR-LLM Social Engineering Attacks | [![arXiv](https://img.shields.io/badge/arXiv-2604.23141-b31b1b?logo=arxiv)](https://arxiv.org/abs/2604.23141) |
| <span style="background-color:#0f766e;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Embodied Data Interfaces</span> | UniDex: A Robot Foundation Suite for Universal Dexterous Hand Control from Egocentric Human Videos | [![arXiv](https://img.shields.io/badge/arXiv-2603.22264-b31b1b?logo=arxiv)](https://arxiv.org/abs/2603.22264) |
| <span style="background-color:#059669;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Persistent Spatial State</span><br><span style="background-color:#475569;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Cross-Cutting Deployment Constraints</span> | Urban Risk-Aware Navigation via VQA-Based Event Maps for People with Low Vision | [![arXiv](https://img.shields.io/badge/arXiv-2605.11782-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.11782) |
| <span style="background-color:#d97706;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Auditable Long-Term Personal Memory</span><br><span style="background-color:#475569;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Cross-Cutting Deployment Constraints</span> | VisGuardian: A Lightweight Group-based Privacy Control Technique For Front Camera Data From AR Glasses in Home Environments | [![arXiv](https://img.shields.io/badge/arXiv-2601.19502-b31b1b?logo=arxiv)](https://arxiv.org/abs/2601.19502) |
| <span style="background-color:#dc2626;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Situated Agentic Action</span><br><span style="background-color:#475569;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Cross-Cutting Deployment Constraints</span> | VisionClaw: Always-On AI Agents through Smart Glasses | [![arXiv](https://img.shields.io/badge/arXiv-2604.03486-b31b1b?logo=arxiv)](https://arxiv.org/abs/2604.03486) |
| <span style="background-color:#2563eb;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">First-Person Perception</span><br><span style="background-color:#7c3aed;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Multimodal Context Modeling</span><br><span style="background-color:#475569;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Cross-Cutting Deployment Constraints</span> | WearVQA: A Visual Question Answering Benchmark for Wearables in Egocentric Authentic Real-World Scenarios | - |
| <span style="background-color:#475569;color:#fff;padding:2px 6px;border-radius:3px;white-space:nowrap;">Cross-Cutting Deployment Constraints</span> | LLM-Oriented Token-Adaptive Knowledge Distillation | - |

## Application Scenes for Smart Glasses

> ⏰ In chronological order, from the earliest to the latest.

### 4.1 Daily Situated Assistance

| Paper Title | Link |
|---|---|
| Towards VQA Models That Can Read | - |
| Mobile-Agent: Autonomous Multi-Modal Mobile Device Agent with Visual Perception | [![arXiv](https://img.shields.io/badge/arXiv-2401.16158-b31b1b?logo=arxiv)](https://arxiv.org/abs/2401.16158) |
| GPT-4V(ision) is a Generalist Web Agent, if Grounded | [![arXiv](https://img.shields.io/badge/arXiv-2401.01614-b31b1b?logo=arxiv)](https://arxiv.org/abs/2401.01614) |
| WebArena: A Realistic Web Environment for Building Autonomous Agents | [![arXiv](https://img.shields.io/badge/arXiv-2307.13854-b31b1b?logo=arxiv)](https://arxiv.org/abs/2307.13854) |
| EgoLife: Towards Egocentric Life Assistant | - |
| TeleEgo: Benchmarking Egocentric AI Assistants in the Wild | [![arXiv](https://img.shields.io/badge/arXiv-2510.23981-b31b1b?logo=arxiv)](https://arxiv.org/abs/2510.23981) |
| Agentic Very Long Video Understanding | - |
| ContextAgent: Context-Aware Proactive LLM Agents with Open-World Sensory Perceptions | - |
| Ego2Web: A Web Agent Benchmark Grounded in Egocentric Videos | [![arXiv](https://img.shields.io/badge/arXiv-2603.22529-b31b1b?logo=arxiv)](https://arxiv.org/abs/2603.22529) |
| EgoExoMem: Cross-View Memory Reasoning over Synchronized Egocentric and Exocentric Videos | [![arXiv](https://img.shields.io/badge/arXiv-2605.18734-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.18734) |
| EgoMemReason: A Memory-Driven Reasoning Benchmark for Long-Horizon Egocentric Video Understanding | [![arXiv](https://img.shields.io/badge/arXiv-2605.09874-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.09874) |
| EgoMonth: A Month-Level Egocentric Video Benchmark for Long-Term Spatiotemporal Memory | [![arXiv](https://img.shields.io/badge/arXiv-2608.13113-b31b1b?logo=arxiv)](https://arxiv.org/abs/2608.13113) |
| EgoSAT: A Comprehensive Benchmark of Egocentric Streaming Interaction Understanding | [![arXiv](https://img.shields.io/badge/arXiv-2606.24422-b31b1b?logo=arxiv)](https://arxiv.org/abs/2606.24422) |
| EGOSTREAM: A Diagnostic Benchmark for Streaming Episodic Memory in Egocentric Vision | [![arXiv](https://img.shields.io/badge/arXiv-2605.31557-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.31557) |
| Egocentric Co-Pilot: Web-Native Smart-Glasses Agents for Assistive Egocentric AI | - |
| GLIMPSE: Real-Time Text Recognition and Contextual Understanding for VQA in Wearables | [![arXiv](https://img.shields.io/badge/arXiv-2602.13479-b31b1b?logo=arxiv)](https://arxiv.org/abs/2602.13479) |
| LightMem-Ego: Your AI Memory for Everyday Life | [![arXiv](https://img.shields.io/badge/arXiv-2607.11487-b31b1b?logo=arxiv)](https://arxiv.org/abs/2607.11487) |
| Exploring Multimodal LMMs for Online Episodic Memory Question Answering on the Edge | [![arXiv](https://img.shields.io/badge/arXiv-2602.22455-b31b1b?logo=arxiv)](https://arxiv.org/abs/2602.22455) |
| OpenGlass: A Sensing-Computing Split Architecture for Local MLLM-Driven Real-Time Visual Assistance | - |
| Personal Visual Context Learning in Large Multimodal Models | [![arXiv](https://img.shields.io/badge/arXiv-2605.10936-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.10936) |
| SAW-Bench: Learning Situated Awareness in the Real World | [![arXiv](https://img.shields.io/badge/arXiv-2602.16682-b31b1b?logo=arxiv)](https://arxiv.org/abs/2602.16682) |
| SUPERGLASSES: Benchmarking Vision Language Models as Intelligent Agents for AI Smart Glasses | - |
| VisionClaw: Always-On AI Agents through Smart Glasses | [![arXiv](https://img.shields.io/badge/arXiv-2604.03486-b31b1b?logo=arxiv)](https://arxiv.org/abs/2604.03486) |
| WearVQA: A Visual Question Answering Benchmark for Wearables in Egocentric Authentic Real-world Scenarios | - |

### 4.2 Accessibility Assistance

| Paper Title | Link |
|---|---|
| NavCog: A Navigational Cognitive Assistant for the Blind | - |
| VizWiz Grand Challenge: Answering Visual Questions from Blind People | [![arXiv](https://img.shields.io/badge/arXiv-1802.08218-b31b1b?logo=arxiv)](https://arxiv.org/abs/1802.08218) |
| LidSonic for Visually Impaired: Green Machine Learning-Based Assistive Smart Glasses with Smart App and Arduino | - |
| Active Noise Cancellation on Open-Ear Smart Glasses | [![arXiv](https://img.shields.io/badge/arXiv-2604.05519-b31b1b?logo=arxiv)](https://arxiv.org/abs/2604.05519) |
| EgoBlind: Towards Egocentric Visual Assistance for the Blind | - |
| Evaluating OCR Performance for Assistive Technology: Effects of Walking Speed, Camera Placement, and Camera Type | - |

### 4.3 Industrial Workflow Support

| Paper Title | Link |
|---|---|
| COIN: A Large-Scale Dataset for Comprehensive Instructional Video Analysis | [![arXiv](https://img.shields.io/badge/arXiv-1903.02874-b31b1b?logo=arxiv)](https://arxiv.org/abs/1903.02874) |
| The IKEA ASM Dataset: Understanding People Assembling Furniture through Actions, Objects and Pose | - |
| Assembly101: A Large-Scale Multi-View Video Dataset for Understanding Procedural Activities | [![arXiv](https://img.shields.io/badge/arXiv-2203.14700-b31b1b?logo=arxiv)](https://arxiv.org/abs/2203.14700) |
| Rescaling Egocentric Vision: Collection, Pipeline and Challenges for EPIC-KITCHENS-100 | [![arXiv](https://img.shields.io/badge/arXiv-2006.13256-b31b1b?logo=arxiv)](https://arxiv.org/abs/2006.13256) |
| Head-Mounted Display Augmented Reality in Manufacturing: A Systematic Review | - |
| HoloAssist: An Egocentric Human Interaction Dataset for Interactive AI Assistants in the Real World | - |
| LabOS: The AI-XR Co-scientist that sees and works with humans | [![arXiv](https://img.shields.io/badge/arXiv-2510.14861-b31b1b?logo=arxiv)](https://arxiv.org/abs/2510.14861) |
| EgoPro-Bench: Benchmarking Personalized Proactive Interaction in Egocentric Video Streams | [![arXiv](https://img.shields.io/badge/arXiv-2605.07299-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.07299) |
| IPIBench: Evaluating Interactive Proactive Intelligence of MLLMs under Continuous Streams | [![arXiv](https://img.shields.io/badge/arXiv-2605.27074-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.27074) |
| Plan, Watch, Recover: A Benchmark and Architectures for Proactive Procedural Assistance | [![arXiv](https://img.shields.io/badge/arXiv-2606.04970-b31b1b?logo=arxiv)](https://arxiv.org/abs/2606.04970) |
| Pro $^2$ Assist: Continuous Step-Aware Proactive Assistance with Multimodal Egocentric Perception for Long-Horizon Procedural Tasks | [![arXiv](https://img.shields.io/badge/arXiv-2605.04227-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.04227) |
| Streaming Interventions: Can Video Large Language Models Correct Mistakes as They Occur? | [![arXiv](https://img.shields.io/badge/arXiv-2606.09547-b31b1b?logo=arxiv)](https://arxiv.org/abs/2606.09547) |

### 4.4 Healthcare and Caregiving

| Paper Title | Link |
|---|---|
| JHU-ISI Gesture and Skill Assessment Working Set (JIGSAWS): A Surgical Activity Dataset for Human Motion Modeling | - |
| EndoNet: A Deep Architecture for Recognition Tasks on Laparoscopic Videos | - |
| A Dataset of Clinically Generated Visual Questions and Answers about Radiology Images | - |
| Augmented Reality in Medical Education: A Systematic Review | - |
| SLAKE: A Semantically-Labeled Knowledge-Enhanced Dataset for Medical Visual Question Answering | - |
| Wearable AR for Restorative Breaks: How Interactive Narrative Experiences Support Relaxation for Young People | - |

### 4.5 Education and Skills Training

| Paper Title | Link |
|---|---|
| Cross-Task Weakly Supervised Learning from Instructional Videos | [![arXiv](https://img.shields.io/badge/arXiv-1903.08272-b31b1b?logo=arxiv)](https://arxiv.org/abs/1903.08272) |
| Ego-1K--A Large-Scale Multiview Video Dataset for Egocentric Vision | [![arXiv](https://img.shields.io/badge/arXiv-2603.13741-b31b1b?logo=arxiv)](https://arxiv.org/abs/2603.13741) |
| Evaluating the Feasibility of Augmented Reality to Support Communication Access for Deaf Students in Experiential Higher Education Contexts | - |

### 4.6 Mobility and Transportation Safety

| Paper Title | Link |
|---|---|
| Are They Going to Cross? A Benchmark Dataset and Baseline for Pedestrian Crosswalk Behavior | - |
| PIE: A Large-Scale Dataset and Models for Pedestrian Intention Estimation and Trajectory Prediction | - |
| BDD100K: A Diverse Driving Dataset for Heterogeneous Multitask Learning | [![arXiv](https://img.shields.io/badge/arXiv-1805.04687-b31b1b?logo=arxiv)](https://arxiv.org/abs/1805.04687) |
| Decoding Pedestrian Crossing Intention from Egocentric Vision via Vision Language Models | [![arXiv](https://img.shields.io/badge/arXiv-2606.09142-b31b1b?logo=arxiv)](https://arxiv.org/abs/2606.09142) |
| Urban Risk-Aware Navigation via VQA-Based Event Maps for People with Low Vision | [![arXiv](https://img.shields.io/badge/arXiv-2605.11782-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.11782) |

### 4.7 Social Interaction and Collaboration

| Paper Title | Link |
|---|---|
| The AMI Meeting Corpus: A Pre-Announcement | - |
| In Situ with Bystanders of Augmented Reality Glasses: Perspectives on Recording and Privacy-Mediating Technologies | - |
| Your Smart Glasses' Camera Bothers Me! Exploring Opt-In and Opt-Out Gestures for Privacy Mediation | - |
| Evaluating a Wearable Camera's Social Acceptability In-the-Wild | - |
| AVA Active Speaker: An Audio-Visual Dataset for Active Speaker Detection | [![arXiv](https://img.shields.io/badge/arXiv-1901.01342-b31b1b?logo=arxiv)](https://arxiv.org/abs/1901.01342) |
| QMSum: A New Benchmark for Query-Based Multi-Domain Meeting Summarization | [![arXiv](https://img.shields.io/badge/arXiv-2104.05972-b31b1b?logo=arxiv)](https://arxiv.org/abs/2104.05972) |
| Conversational Successes and Breakdowns in Everyday Smart Glasses Use | [![arXiv](https://img.shields.io/badge/arXiv-2602.22340-b31b1b?logo=arxiv)](https://arxiv.org/abs/2602.22340) |
| H2HMem: A Multimodal Memory Benchmark for Agents in Human-Human Interactions | [![arXiv](https://img.shields.io/badge/arXiv-2606.09461-b31b1b?logo=arxiv)](https://arxiv.org/abs/2606.09461) |
| Mind the Gap: Mapping Wearer--Bystander Privacy Tensions and Context-Adaptive Pathways for Camera Glasses | - |
| Position: Life-Logging Video Streams Make the Privacy-Utility Trade-off Inevitable | [![arXiv](https://img.shields.io/badge/arXiv-2605.10404-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.10404) |
| Reshaping Inclusive Interpersonal Dynamics through Smart Glasses in Mixed-Vision Social Activities | - |
| VisGuardian: A Lightweight Group-based Privacy Control Technique For Front Camera Data From AR Glasses in Home Environments | [![arXiv](https://img.shields.io/badge/arXiv-2601.19502-b31b1b?logo=arxiv)](https://arxiv.org/abs/2601.19502) |

### 4.8 Spatial Intelligence

| Paper Title | Link |
|---|---|
| Matterport3D: Learning from RGB-D Data in Indoor Environments | [![arXiv](https://img.shields.io/badge/arXiv-1709.06158-b31b1b?logo=arxiv)](https://arxiv.org/abs/1709.06158) |
| ScanNet: Richly-Annotated 3D Reconstructions of Indoor Scenes | [![arXiv](https://img.shields.io/badge/arXiv-1703.08805-b31b1b?logo=arxiv)](https://arxiv.org/abs/1703.08805) |
| Embodied Question Answering | [![arXiv](https://img.shields.io/badge/arXiv-1711.11583-b31b1b?logo=arxiv)](https://arxiv.org/abs/1711.11583) |
| Vision-and-Language Navigation: Interpreting Visually-Grounded Navigation Instructions in Real Environments | [![arXiv](https://img.shields.io/badge/arXiv-1711.07280-b31b1b?logo=arxiv)](https://arxiv.org/abs/1711.07280) |
| VINS-Mono: A Robust and Versatile Monocular Visual-Inertial State Estimator | [![arXiv](https://img.shields.io/badge/arXiv-1708.03852-b31b1b?logo=arxiv)](https://arxiv.org/abs/1708.03852) |
| Habitat: A Platform for Embodied AI Research | [![arXiv](https://img.shields.io/badge/arXiv-1904.01201-b31b1b?logo=arxiv)](https://arxiv.org/abs/1904.01201) |
| REVERIE: Remote Embodied Visual Referring Expression in Real Indoor Environments | [![arXiv](https://img.shields.io/badge/arXiv-1904.02716-b31b1b?logo=arxiv)](https://arxiv.org/abs/1904.02716) |
| DROID-SLAM: Deep Visual SLAM for Monocular, Stereo, and RGB-D Cameras | [![arXiv](https://img.shields.io/badge/arXiv-2108.10869-b31b1b?logo=arxiv)](https://arxiv.org/abs/2108.10869) |
| ORB-SLAM3: An Accurate Open-Source Library for Visual, Visual-Inertial, and Multimap SLAM | [![arXiv](https://img.shields.io/badge/arXiv-2007.11898-b31b1b?logo=arxiv)](https://arxiv.org/abs/2007.11898) |
| Aria Digital Twin: A New Benchmark Dataset for Egocentric 3D Machine Perception | - |
| Project Aria: A New Tool for Egocentric Multi-Modal AI Research | [![arXiv](https://img.shields.io/badge/arXiv-2308.13561-b31b1b?logo=arxiv)](https://arxiv.org/abs/2308.13561) |
| OpenEQA: Embodied Question Answering in the Era of Foundation Models | - |
| LEVIO: Lightweight Embedded Visual Inertial Odometry for Resource-Constrained Devices | - |
| EgoForge: Goal-Directed Egocentric World Simulator | [![arXiv](https://img.shields.io/badge/arXiv-2603.20169-b31b1b?logo=arxiv)](https://arxiv.org/abs/2603.20169) |
| EgoProx: Evaluating MLLMs on Egocentric 3D Proximity Reasoning Across a Cognitive Hierarchy | [![arXiv](https://img.shields.io/badge/arXiv-2605.24456-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.24456) |
| Latent Spatial Memory for Video World Models | [![arXiv](https://img.shields.io/badge/arXiv-2606.09828-b31b1b?logo=arxiv)](https://arxiv.org/abs/2606.09828) |
| Do MLLMs Understand Pointing? Benchmarking and Enhancing Referential Reasoning in Egocentric Vision | - |
| In the Eye of the Beholder: Joint Learning of Gaze and Actions in First Person Video | - |
| Pandora: Articulated 3D Scene Graphs from Egocentric Vision | [![arXiv](https://img.shields.io/badge/arXiv-2603.28732-b31b1b?logo=arxiv)](https://arxiv.org/abs/2603.28732) |
| SpatialWorld: Benchmarking Interactive Spatial Reasoning of Multimodal Agents in Real-World Tasks | [![arXiv](https://img.shields.io/badge/arXiv-2606.09669-b31b1b?logo=arxiv)](https://arxiv.org/abs/2606.09669) |
| Intention-Aware Semantic Agent Communications for AI Glasses | [![arXiv](https://img.shields.io/badge/arXiv-2604.23691-b31b1b?logo=arxiv)](https://arxiv.org/abs/2604.23691) |

### 4.9 Embodied Intelligence

| Paper Title | Link |
|---|---|
| Ego4D: Around the World in 3,000 Hours of Egocentric Video | [![arXiv](https://img.shields.io/badge/arXiv-2110.07058-b31b1b?logo=arxiv)](https://arxiv.org/abs/2110.07058) |
| R3M: A Universal Visual Representation for Robot Manipulation | [![arXiv](https://img.shields.io/badge/arXiv-2203.12601-b31b1b?logo=arxiv)](https://arxiv.org/abs/2203.12601) |
| RT-1: Robotics Transformer for Real-World Control at Scale | [![arXiv](https://img.shields.io/badge/arXiv-2212.06817-b31b1b?logo=arxiv)](https://arxiv.org/abs/2212.06817) |
| Do As I Can, Not As I Say: Grounding Language in Robotic Affordances | [![arXiv](https://img.shields.io/badge/arXiv-2204.01691-b31b1b?logo=arxiv)](https://arxiv.org/abs/2204.01691) |
| BridgeData V2: A Dataset for Robot Learning at Scale | [![arXiv](https://img.shields.io/badge/arXiv-2308.12952-b31b1b?logo=arxiv)](https://arxiv.org/abs/2308.12952) |
| DROID: A Large-Scale In-the-Wild Robot Manipulation Dataset | [![arXiv](https://img.shields.io/badge/arXiv-2403.12945-b31b1b?logo=arxiv)](https://arxiv.org/abs/2403.12945) |
| Ego-Exo4D: Understanding Skilled Human Activity from First- and Third-Person Perspectives | [![arXiv](https://img.shields.io/badge/arXiv-2311.18259-b31b1b?logo=arxiv)](https://arxiv.org/abs/2311.18259) |
| Open X-Embodiment: Robotic Learning Datasets and RT-X Models: Open X-Embodiment Collaboration 0 | [![arXiv](https://img.shields.io/badge/arXiv-2310.08864-b31b1b?logo=arxiv)](https://arxiv.org/abs/2310.08864) |
| EgoBridge: Domain Adaptation for Generalizable Imitation from Egocentric Human Data | - |
| EgoMI: Learning Active Vision and Whole-Body Manipulation from Egocentric Human Demonstrations | [![arXiv](https://img.shields.io/badge/arXiv-2511.00153-b31b1b?logo=arxiv)](https://arxiv.org/abs/2511.00153) |
| EgoVLA: Learning Vision-Language-Action Models from Egocentric Human Videos | [![arXiv](https://img.shields.io/badge/arXiv-2507.12440-b31b1b?logo=arxiv)](https://arxiv.org/abs/2507.12440) |
| EgoMimic: Scaling Imitation Learning via Egocentric Video | - |
| EgoZero: Robot Learning from Smart Glasses | [![arXiv](https://img.shields.io/badge/arXiv-2505.20290-b31b1b?logo=arxiv)](https://arxiv.org/abs/2505.20290) |
| HD-EPIC: A Highly-Detailed Egocentric Video Dataset | - |
| Scalable Vision-Language-Action Model Pretraining for Robotic Manipulation with Real-Life Human Activity Videos | [![arXiv](https://img.shields.io/badge/arXiv-2510.21571-b31b1b?logo=arxiv)](https://arxiv.org/abs/2510.21571) |
| ImitDiff: Transferring Foundation-Model Priors for Distraction-Robust Visuomotor Policy | - |
| ActiveMimic: Egocentric Video Pretraining with Active Perception | [![arXiv](https://img.shields.io/badge/arXiv-2606.06194-b31b1b?logo=arxiv)](https://arxiv.org/abs/2606.06194) |
| ActiveGlasses: Learning Manipulation with Active Vision from Ego-Centric Human Demonstration | [![arXiv](https://img.shields.io/badge/arXiv-2604.08534-b31b1b?logo=arxiv)](https://arxiv.org/abs/2604.08534) |
| AoE: Always-On Egocentric Human Video Collection for Embodied AI | [![arXiv](https://img.shields.io/badge/arXiv-2602.23893-b31b1b?logo=arxiv)](https://arxiv.org/abs/2602.23893) |
| EPIC: A System Framework for Efficient Egocentric Perception on Embodied AR Glasses | [![arXiv](https://img.shields.io/badge/arXiv-2606.15859-b31b1b?logo=arxiv)](https://arxiv.org/abs/2606.15859) |
| EgoEngine: From Egocentric Human Videos to High-Fidelity Dexterous Robot Demonstrations | [![arXiv](https://img.shields.io/badge/arXiv-2606.12604-b31b1b?logo=arxiv)](https://arxiv.org/abs/2606.12604) |
| EgoKit: Towards Unified Low-Cost Egocentric Data Collection with Heterogeneous Devices | [![arXiv](https://img.shields.io/badge/arXiv-2605.16797-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.16797) |
| EgoScale: Scaling Dexterous Manipulation with Diverse Egocentric Human Data | [![arXiv](https://img.shields.io/badge/arXiv-2602.16710-b31b1b?logo=arxiv)](https://arxiv.org/abs/2602.16710) |
| EgoTactile: Learning Grasp Pressure for Everyday Objects from Egocentric Video | [![arXiv](https://img.shields.io/badge/arXiv-2606.09243-b31b1b?logo=arxiv)](https://arxiv.org/abs/2606.09243) |
| EgoWAM: World Action Models Beyond Pixels with In-the-Wild Egocentric Human Data | - |
| EgoDex: Learning Dexterous Manipulation from Large-Scale Egocentric Video | - |
| Human Universal Grasping | [![arXiv](https://img.shields.io/badge/arXiv-2606.17054-b31b1b?logo=arxiv)](https://arxiv.org/abs/2606.17054) |
| HumanEgo: Zero-Shot Robot Learning from Minutes of Human Egocentric Videos | [![arXiv](https://img.shields.io/badge/arXiv-2605.24934-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.24934) |
| HumanNet: Scaling Human-Centric Video Learning to One Million Hours | [![arXiv](https://img.shields.io/badge/arXiv-2605.06747-b31b1b?logo=arxiv)](https://arxiv.org/abs/2605.06747) |
| Open-AoE: An Open Egocentric Manipulation Dataset and Toolchain for Embodied Learning | [![arXiv](https://img.shields.io/badge/arXiv-2607.14183-b31b1b?logo=arxiv)](https://arxiv.org/abs/2607.14183) |
| UniDex: A Robot Foundation Suite for Universal Dexterous Hand Control from Egocentric Human Videos | [![arXiv](https://img.shields.io/badge/arXiv-2603.22264-b31b1b?logo=arxiv)](https://arxiv.org/abs/2603.22264) |
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