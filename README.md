# ⭐ Awesome Audio Super-Resolution and Bandwidth Extension

A curated collection of papers, resources, datasets, and benchmarks for **Audio Super-Resolution (SR)** and **Bandwidth Extension (BWE)**, covering the evolution from **discriminative to generative models**.

This repository accompanies our survey:

> **A Survey of Advancing Audio Super-Resolution and Bandwidth Extension from Discriminative to Generative Models**

If you find any missing papers, incorrect information, or useful resources, please feel free to open an **Issue** or submit a **Pull Request**. Contributions are very welcome!

---

<p align="center">
  <img src="/Timeline2.png" width="95%">
</p>

<p align="center">
  <em>Timeline of audio super-resolution and bandwidth extension methods, from discriminative to generative models.</em>
</p>

---

## 📜 Citation

If you find our survey or this repository useful for your research, please consider citing our paper and giving this repository a ⭐.

```bibtex
@article{yang2026survey,
  title={A survey of advancing audio super-resolution and bandwidth extension from discriminative to generative models},
  author={Yang, Ningyuan and Li, Yize and Cuji, Diego A and Corey, Ryan M and Zhao, Pu and Lin, Xue and Singer, Andrew C},
  journal={arXiv preprint arXiv:2605.16681},
  year={2026}
}
```

---

## 📢 News

* **2026/08** 🔥 Repository released.
* **2026/XX** 🔥 Our survey is available on arXiv.
* More papers and resources will be continuously added.

---

## 📑 Table of Contents

* [Overview](#-overview)
* [Discriminative Models](#-discriminative-models)

  * [MLP/RNN/CNN](#mlp-based-models)
  * [Transformers](#transformer-based-models)
  * [State Space Models (Mamba)](#state-space--mamba-models)
* [Generative Models](#-generative-models)

  * [Autoregressive Models](#autoregressive-models)
  * [Variational Autoencoders (VAEs)](#variational-autoencoders)
  * [Generative Adversarial Networks (GANs)](#gan-based-models)
  * [Diffusion-based Models](#diffusion--score-based-models)
  * [Flow-based Models](#flow-based-models)
  * [Schrödinger Bridge](#schrödinger-bridge-models)
---

# 📖 Overview

Audio super-resolution and bandwidth extension aim to reconstruct missing high-frequency information from bandwidth-limited audio signals. 

Over the past decade, methods have evolved from deterministic **discriminative models**, which directly predict missing frequency components, toward **generative models** capable of modeling the distribution of plausible high-frequency content. 

This repository organizes representative methods according to their primary modeling paradigms and provides links to papers and official implementations whenever available.

---

# 🔷 Discriminative Models

## MLP/RNN/CNN

### Earlier Works

* `[Venue'YY]` **Paper Title** [[Paper](PAPER_URL)] [[Code](CODE_URL)]

---

## Transformers

### 2025

* **[ArXiv'25]** A High-Fidelity Speech Super Resolution Network using a Complex Global Attention Module with Spectro-Temporal Loss [[Paper](https://arxiv.org/abs/2507.00229)]

* **[InterSpeech'25]** A Neural Codec Approach for Noise-Robust Bandwidth Expansion [[Paper](https://www.isca-archive.org/interspeech_2025/liu25p_interspeech.pdf)]

### 2024

* `[Venue'24]` **Paper Title** [[Paper](PAPER_URL)] [[Code](CODE_URL)]

---

## State Space Models (Mamba)

### 2026

* `[Venue'26]` **Paper Title** [[Paper](PAPER_URL)] [[Code](CODE_URL)]

### 2025

* `[Venue'25]` **VM-ASR** [[Paper](PAPER_URL)] [[Code](CODE_URL)]

---

# ✨ Generative Models

Generative approaches model the conditional distribution of missing audio information and can synthesize plausible high-frequency components beyond deterministic point estimates.

---

## Autoregressive Models

### 2024

* `[Venue'24]` **Paper Title** [[Paper](PAPER_URL)] [[Code](CODE_URL)]

### Earlier Works

* `[Venue'YY]` **Paper Title** [[Paper](PAPER_URL)]

---

## Variational Autoencoders (VAEs)

### 2024

* `[Venue'24]` **Paper Title** [[Paper](PAPER_URL)] [[Code](CODE_URL)]

### Earlier Works

* `[Venue'YY]` **Paper Title** [[Paper](PAPER_URL)]

---

## Generative Adversarial Networks

### 2025

* `[Venue'25]` **Paper Title** [[Paper](PAPER_URL)] [[Code](CODE_URL)]

### 2024

* `[Venue'24]` **AP-BWE** [[Paper](PAPER_URL)] [[Code](CODE_URL)]

### 2023

* `[Venue'23]` **AERO** [[Paper](PAPER_URL)] [[Code](CODE_URL)]

### Earlier Works

* `[Venue'YY]` **Paper Title** [[Paper](PAPER_URL)] [[Code](CODE_URL)]

---

## Diffusion-based Models

### 2025

* `[Venue'25]` **Paper Title** [[Paper](PAPER_URL)] [[Code](CODE_URL)]

### 2024

* `[Venue'24]` **AudioSR** [[Paper](PAPER_URL)] [[Code](CODE_URL)]

### 2023

* `[Venue'23]` **NU-Wave2** [[Paper](PAPER_URL)] [[Code](CODE_URL)]

* `[Venue'23]` **UDM+** [[Paper](PAPER_URL)] [[Code](CODE_URL)]

### Earlier Works

* `[Venue'YY]` **NU-Wave** [[Paper](PAPER_URL)] [[Code](CODE_URL)]

---

## Flow-based Models

### 2026

* `[Venue'26]` **FLowHigh** [[Paper](PAPER_URL)] [[Code](CODE_URL)]

* `[Venue'26]` **UniverSR** [[Paper](PAPER_URL)] [[Code](CODE_URL)]

### 2025

* `[Venue'25]` **Paper Title** [[Paper](PAPER_URL)] [[Code](CODE_URL)]

---

## Schrödinger Bridge

### 2025

* `[Venue'25]` **Paper Title** [[Paper](PAPER_URL)] [[Code](CODE_URL)]

### 2024

* `[Venue'24]` **A2SB / Related Method** [[Paper](PAPER_URL)] [[Code](CODE_URL)]

---
