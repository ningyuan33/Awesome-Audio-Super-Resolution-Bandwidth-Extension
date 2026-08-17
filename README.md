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

# 🔷 Discriminative Models

## MLP/RNN/CNN

### 2024

* **[ICASSP'24]** Speaker Adaptation For Enhancement Of Bone-Conducted Speech [[Paper](https://ieeexplore.ieee.org/document/10447322)]

### 2023

* **[Interspeech'23]** Noise-Robust Bandwidth Expansion for 8K Speech Recordings [[Paper](https://www.isca-archive.org/interspeech_2023/lin23f_interspeech.html)]

* **[SPL'23]** Restoration of Bone-Conducted Speech With U-Net-Like Model and Energy Distance Loss [[Paper](https://ieeexplore.ieee.org/document/10374184)]

### Earlier Works

* **[Interspeech'21]** A Two-Stage Approach to Speech Bandwidth Extension [[Paper](https://www.isca-archive.org/interspeech_2021/lin21d_interspeech.html)]

---

## Transformers

### 2025

* **[ArXiv'25]** A High-Fidelity Speech Super Resolution Network using a Complex Global Attention Module with Spectro-Temporal Loss [[Paper](https://arxiv.org/abs/2507.00229)]

* **[Interspeech'25]** A Neural Codec Approach for Noise-Robust Bandwidth Expansion [[Paper](https://www.isca-archive.org/interspeech_2025/liu25p_interspeech.pdf)] [[Demo](https://winkee520.github.io/NRBWE/)]

### 2024

* **[ICASSP'24]** Class: Continual Learning Approach for Speech Super-Resolution [[Paper](https://ieeexplore.ieee.org/document/10445917)]

* **[IMWUT'24]** TRAMBA: A Hybrid Transformer and Mamba Architecture for Practical Audio and Bone Conduction Speech Super Resolution and Enhancement on Mobile and Wearable Platforms [[Paper](https://dl.acm.org/doi/pdf/10.1145/3699757)] [[Code](https://github.com/IMEC-Northwestern/TRAMBA)]

### Earlier Works

* **[ICASSP'22]** Tunet: A Block-Online Bandwidth Extension Model Based On Transformers And Self-Supervised Pretraining [[Paper](https://ieeexplore.ieee.org/document/9747699)] [[Code](https://github.com/nxtproduct/tunet)]

* **[MLSP'21]** Self-Attention for Audio Super-Resolution [[Paper](https://ieeexplore.ieee.org/document/9596082)] [[Code](https://github.com/ncarraz/AFILM)]

---

## State Space Models (Mamba)

### 2024

* **[IMWUT'24]** TRAMBA: A Hybrid Transformer and Mamba Architecture for Practical Audio and Bone Conduction Speech Super Resolution and Enhancement on Mobile and Wearable Platforms [[Paper](https://dl.acm.org/doi/pdf/10.1145/3699757)] [[Code](https://github.com/IMEC-Northwestern/TRAMBA)]

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
