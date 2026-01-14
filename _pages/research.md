---
permalink: /research/
title: "Research Interests"
author_profile: true
---

Understanding and optimizing wireless networks is at the core of my research. I explore theory-driven approaches that stay close to real-world implementations, with a particular focus on the intersection between communications and machine learning.

## Focus Areas

- **Foundation Models for Wireless Communications**  
  Building large-scale neural representations of spectrum and channel behavior that transfer across bands, hardware, and deployment scenarios—enabling few-shot adaptation for tasks like signal classification, interference detection, and beam management.

- **Massive MIMO Communications**  
  Designing scalable transceiver architectures that extract the full potential of large antenna arrays under realistic hardware and channel constraints.

- **Integrated Sensing and Communication (ISAC)**  
  Building joint sensing-and-communication frameworks that enable mobile platforms to perceive their environment while maintaining robust connectivity.

## Current Directions

- **Wireless baseband spectrogram foundation models (LWM-Spectro)**  
  LWM-Spectro is a transformer-based foundation model pretrained on large-scale received I/Q signals represented as time–frequency spectrograms. It combines self-supervised masked modeling, contrastive learning, and a mixture-of-experts (MoE) architecture to learn transferable wireless representations that perform strongly on downstream tasks (e.g., modulation classification and joint SNR/mobility recognition), even with minimal labeled data.
  
  <span class="nk-research-links">Links: <a href="https://arxiv.org/abs/2601.08780" target="_blank" rel="noopener">arXiv</a> | <a href="https://huggingface.co/spaces/wi-lab/LWM-Spectro" target="_blank" rel="noopener"><img class="nk-inline-icon" src="/images/huggingface_logo-noborder.svg" alt="" aria-hidden="true"/>Hugging Face</a></span>
