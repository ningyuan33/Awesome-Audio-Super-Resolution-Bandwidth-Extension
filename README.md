# ⭐ Awesome Audio Super-Resolution and Bandwidth Extension

A curated collection of papers, resources, datasets, and benchmarks for **Audio Super-Resolution (SR)** and **Bandwidth Extension (BWE)**, covering the evolution from **discriminative to generative models**.

This repository accompanies our survey:

> **A Survey of Advancing Audio Super-Resolution and Bandwidth Extension from Discriminative to Generative Models**

If you find any missing papers, incorrect information, or useful resources, please feel free to open an **Issue** or submit a **Pull Request**. Contributions are very welcome!

---

<p align="center">
  <img src="/Timeline.png" width="95%">
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

  * [Autoregressive](#autoregressive-models)
  * [Variational Autoencoders (VAEs)](#variational-autoencoders)
  * [Generative Adversarial Networks (GANs)](#gan-based-models)
  * [Diffusion](#diffusion--score-based-models)
  * [Flow](#flow-based-models)
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

* **[TASLP'21]** Towards Robust Speech Super-Resolution [[Paper](https://ieeexplore.ieee.org/document/9335252)]

* **[ICASSP'20]** Time-Frequency Loss for CNN Based Speech Super-Resolution [[Paper](https://ieeexplore.ieee.org/document/9053712)]

* **[ICASSP'20]** A Time-Frequency Network with Channel Attention and Non-Local Modules for Artificial Bandwidth Extension [[Paper](https://ieeexplore.ieee.org/document/9053769)]

* **[ICASSP'20]** Time-Domain Neural Network Approach for Speech Bandwidth Extension [[Paper](https://ieeexplore.ieee.org/document/9054551)]

* **[Interspeech'20]** Speaker and Phoneme-Aware Speech Bandwidth Extension with Residual Dual-Path Network [[Paper](https://www.isca-archive.org/interspeech_2020/hou20c_interspeech.html)]

* **[NeurIPS'19]** Temporal FiLM: Capturing Long-Range Sequence Dependencies with Feature-Wise Modulation [[Paper](https://proceedings.neurips.cc/paper_files/paper/2019/file/2afc4dfb14e55c6face649a1d0c1025b-Paper.pdf)] [[Code](https://github.com/kuleshov/audio-super-res)]

* **[ICASSP'18]** Time-Frequency Networks for Audio Super-Resolution [[Paper](https://ieeexplore.ieee.org/document/8462049)] [[Code](https://github.com/moodoki/tfnet)]

* **[ICASSP'18]** Blind Bandwidth Extension Based on Convolutional and Recurrent Deep Neural Networks [[Paper](https://ieeexplore.ieee.org/document/8462049)]

* **[ICASSP'18]** A Simple Cepstral Domain DNN Approach to Artificial Speech Bandwidth Extension [[Paper](https://ieeexplore.ieee.org/document/8462362)]

* **[TASLP'18]** Waveform Modeling and Generation Using Hierarchical Recurrent Neural Networks for Speech Bandwidth Extension [[Paper](https://ieeexplore.ieee.org/document/8270683)]

* **[TASLP'18]** Artificial Speech Bandwidth Extension Using Deep Neural Networks for Wideband Spectral Envelope Estimation [[Paper](https://ieeexplore.ieee.org/document/8063328)]

* **[Interspeech'17]** Waveform Modeling Using Stacked Dilated Convolutional Neural Networks for Speech Bandwidth Extension [[Paper](https://www.isca-archive.org/interspeech_2017/gu17_interspeech.html)]

* **[ICLR Workshop'17]** Audio Super Resolution using Neural Networks [[Paper](https://arxiv.org/abs/1708.00853)] [[Code](https://github.com/kuleshov/audio-super-res)]

* **[Interspeech'16]** Speech Bandwidth Extension Using Bottleneck Features and Deep Recurrent Neural Networks [[Paper](https://www.isca-archive.org/interspeech_2016/gu16b_interspeech.html)]

* **[Interspeech'16]** A Novel Research to Artificial Bandwidth Extension Based on Deep BLSTM Recurrent Neural Networks and Exemplar-Based Sparse Representation [[Paper](https://www.isca-archive.org/interspeech_2016/liu16k_interspeech.html)]

* **[IWAENC'16]** Artificial bandwidth extension using deep neural networks for spectral envelope estimation [[Paper](https://ieeexplore.ieee.org/document/7602894)]

* **[ICASSP'15]** A deep neural network approach to speech bandwidth expansion [[Paper](https://ieeexplore.ieee.org/document/7178801)]

* **[Interspeech'15]** A Novel Method of Artificial Bandwidth Extension Using Deep Architecture [[Paper](https://www.isca-archive.org/interspeech_2015/liu15g_interspeech.html)]

* **[Interspeech'15]** Speech bandwidth expansion based on deep neural networks [[Paper](https://www.isca-archive.org/interspeech_2015/wang15i_interspeech.html)]

* **[Interspeech'15]** DNN-based speech bandwidth expansion and its application to adding high-frequency missing features for automatic speech recognition of narrowband speech [[Paper](https://www.isca-archive.org/interspeech_2015/li15d_interspeech.html)]

* **[IJCNN'15]** Restoring high frequency spectral envelopes using neural networks for speech bandwidth extension [[Paper](https://ieeexplore.ieee.org/document/7280483)]

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

## Autoregressive

### Earlier Works

* **[WASPAA'19]** Speech Bandwidth Extension with Wavenet [[Paper](https://ieeexplore.ieee.org/document/8937169)]

* **[ISCSLP'18]** Speech Super-Resolution Using Parallel WaveNet [[Paper](https://ieeexplore.ieee.org/document/8706637)]

---

## Variational Autoencoders (VAEs)

### 2024

* **[ACM MM'24]** Time-Frequency Domain Fusion Enhancement for Audio Super-Resolution [[Paper](https://dl.acm.org/doi/10.1145/3664647.3681486)]

### Earlier Works

* **[ICASSP'20]** Artificial Bandwidth Extension Using Conditional Variational Auto-encoders and Adversarial Learning [[Paper](https://ieeexplore.ieee.org/document/9053737)]

---

## Generative Adversarial Networks (GANs)

### 2025

* `[Venue'25]` **Paper Title** [[Paper](PAPER_URL)] [[Code](CODE_URL)]

### 2024

* `[Venue'24]` **AP-BWE** [[Paper](PAPER_URL)] [[Code](CODE_URL)]

### 2023

* `[Venue'23]` **AERO** [[Paper](PAPER_URL)] [[Code](CODE_URL)]

### Earlier Works

* `[Venue'YY]` **Paper Title** [[Paper](PAPER_URL)] [[Code](CODE_URL)]

---

## Diffusion

### 2026
* **[ArXiv'26]** FastWave: Optimized Diffusion Model for Audio Super-Resolution [[Paper](https://arxiv.org/abs/2603.04122)] [[Code](https://github.com/Nikait/FastWave)]

* **[AAAI'26]** Inference-time Scaling for Diffusion-based Audio Super-resolution [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/38520)] [[Demo](https://racerk.github.io/tt-scale-audiosr/)]

### 2025

* **[ICASSP'25]** FlashSR: One-step Versatile Audio Super-resolution via Diffusion Distillation [[Paper](https://ieeexplore.ieee.org/document/10889472)] [[Demo](https://jakeoneijk.github.io/flashsr-demo/)]

* **[ICASSP'25]** Vector Quantized Diffusion Model Based Speech Bandwidth Extension [[Paper](https://ieeexplore.ieee.org/document/10889180)] 

### 2024

* **[ICASSP'24]** Audiosr: Versatile Audio Super-Resolution at Scale [[Paper](https://ieeexplore.ieee.org/document/10447246)] [[Code](https://github.com/haoheliu/versatile_audio_super_resolution)]

* **[TASLP'24]** Blind Audio Bandwidth Extension: A Diffusion-Based Zero-Shot Approach [[Paper](https://ieeexplore.ieee.org/document/10768977)] [[Code](https://github.com/eloimoliner/BABE)]

### 2023

* `[Venue'23]` **NU-Wave2** [[Paper](PAPER_URL)] [[Code](CODE_URL)]

* `[Venue'23]` **UDM+** [[Paper](PAPER_URL)] [[Code](CODE_URL)]

### Earlier Works

* `[Venue'YY]` **NU-Wave** [[Paper](PAPER_URL)] [[Code](CODE_URL)]

---

## Flow

### 2026

* **[ArXiv'26]** LatentFlowSR: High-Fidelity Audio Super-Resolution via Noise-Robust Latent Flow Matching [[Paper](https://arxiv.org/abs/2604.09188)]

* **[ArXiv'26]** CodecFlow: Efficient Bandwidth Extension via Conditional Flow Matching in Neural Codec Latent Space [[Paper](https://arxiv.org/abs/2603.02022)]

* **[ICASSP'26]** Universr: Unified and Versatile Audio Super-Resolution Via Vocoder-Free Flow Matching [[Paper](https://ieeexplore.ieee.org/document/11460830)] [[Code](https://github.com/woongzip1/UniverSR)]

* **[ICASSP'26]** SAGA-SR: Semantically and Acoustically Guided Audio Super-Resolution [[Paper](https://ieeexplore.ieee.org/document/11460886)] [[Code](https://github.com/jakeoneijk/SAGA-SR)]

* **[ICASSP'26]** Towards Real-Time Generative Speech Restoration with Flow-Matching [[Paper](https://ieeexplore.ieee.org/document/11463015)]

* **[ICASSP'26]** Single-Step Controllable Music Bandwidth extension with Flow Matching [[Paper](https://ieeexplore.ieee.org/document/11461402)]


### 2025

* **[ICASSP'25]** FLowHigh: Towards Efficient and High-Quality Audio Super-Resolution with Single-Step Flow Matching [[Paper](https://ieeexplore.ieee.org/document/10888772)] [[Code](https://github.com/jjunak-yun/FLowHigh_code)]

* **[ICASSP'25]** Generative Speech Foundation Model Pretraining for High-Quality Speech Extraction and Restoration [[Paper](https://ieeexplore.ieee.org/document/10888830)] [[Demo](https://kuray107.github.io/ssl_gen25-examples/index.html)]

* **[TASLP'25]** Real-Time Streamable Generative Speech Restoration With Flow Matching [[Paper](https://ieeexplore.ieee.org/document/11533884)] [[Code](https://github.com/sp-uhh/streamfm)]

### Earlier Works
* **[Interspeech'21]** WSRGlow: A Glow-Based Waveform Generative Model for Audio Super-Resolution [[Paper](https://www.isca-archive.org/interspeech_2021/zhang21k_interspeech.html)] [[Code](https://github.com/zkx06111/WSRGlow)]

---

## Schrödinger Bridge

### 2025

* **[NeurIPS'25]** Audio Super-Resolution with Latent Bridge Models [[Paper](https://papers.neurips.cc/paper_files/paper/2025/file/4572bc2f514e627914cbe60d0398a2d1-Paper-Conference.pdf)] [[Demo](https://audiolbm.github.io/?ref=aiartweekly)]

* **[ICASSP'25]** Bridge-SR: Schrödinger Bridge for Efficient SR [[Paper](https://ieeexplore.ieee.org/document/10890104)]

* **[ArXiv'25]** A2SB: Audio-to-Audio Schrodinger Bridges [[Paper](https://arxiv.org/abs/2501.11311)] [[Code](https://github.com/NVIDIA/diffusion-audio-restoration)]

---
