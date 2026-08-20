# ⭐ Awesome Audio Super-Resolution and Bandwidth Extension

📚 A curated collection of papers, resources, datasets, and benchmarks for **Audio Super-Resolution (SR)** and **Bandwidth Extension (BWE)**, covering the evolution from **discriminative to generative models**.

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

* **2026/08** 🔥🔥 Repository is released.
* **2026/06** 🔥🔥 Our paper "[A survey of advancing audio super-resolution and bandwidth extension from discriminative to generative models](https://arxiv.org/abs/2605.16681v2)" is available on arXiv.
* More papers and resources will be continuously added.

---

## 📑 Table of Contents
* [Discriminative Models](#-discriminative-models)
  * [MLP/RNN/CNN](#mlprnncnn)
  * [Transformers](#transformers)
  * [State Space Models (Mamba)](#state-space-models-mamba)

* [Generative Models](#-generative-models)
  * [Autoregressive](#autoregressive)
  * [Variational Autoencoders (VAEs)](#variational-autoencoders-vaes)
  * [Generative Adversarial Networks (GANs)](#generative-adversarial-networks-gans)
  * [Diffusion](#diffusion)
  * [Flow](#flow)
  * [Schrödinger Bridge](#schrödinger-bridge)
---

# 🔷 Discriminative Models

## [MLP/RNN/CNN]

### 2024

* **[ICASSP'24]** Speaker Adaptation For Enhancement Of Bone-Conducted Speech [[Paper](https://ieeexplore.ieee.org/document/10447322)]

### 2023

* **[INTERSPEECH'23]** Noise-Robust Bandwidth Expansion for 8K Speech Recordings [[Paper](https://www.isca-archive.org/interspeech_2023/lin23f_interspeech.html)]

* **[SPL'23]** Restoration of Bone-Conducted Speech With U-Net-Like Model and Energy Distance Loss [[Paper](https://ieeexplore.ieee.org/document/10374184)]

### Earlier Works

* **[INTERSPEECH'21]** A Two-Stage Approach to Speech Bandwidth Extension [[Paper](https://www.isca-archive.org/interspeech_2021/lin21d_interspeech.html)]

* **[TASLP'21]** Towards Robust Speech Super-Resolution [[Paper](https://ieeexplore.ieee.org/document/9335252)]

* **[ICASSP'20]** Time-Frequency Loss for CNN Based Speech Super-Resolution [[Paper](https://ieeexplore.ieee.org/document/9053712)]

* **[ICASSP'20]** A Time-Frequency Network with Channel Attention and Non-Local Modules for Artificial Bandwidth Extension [[Paper](https://ieeexplore.ieee.org/document/9053769)]

* **[ICASSP'20]** Time-Domain Neural Network Approach for Speech Bandwidth Extension [[Paper](https://ieeexplore.ieee.org/document/9054551)]

* **[INTERSPEECH'20]** Speaker and Phoneme-Aware Speech Bandwidth Extension with Residual Dual-Path Network [[Paper](https://www.isca-archive.org/interspeech_2020/hou20c_interspeech.html)]

* **[NeurIPS'19]** Temporal FiLM: Capturing Long-Range Sequence Dependencies with Feature-Wise Modulation [[Paper](https://proceedings.neurips.cc/paper_files/paper/2019/file/2afc4dfb14e55c6face649a1d0c1025b-Paper.pdf)] [[Code](https://github.com/kuleshov/audio-super-res)]

* **[ICASSP'18]** Time-Frequency Networks for Audio Super-Resolution [[Paper](https://ieeexplore.ieee.org/document/8462049)] [[Code](https://github.com/moodoki/tfnet)]

* **[ICASSP'18]** Blind Bandwidth Extension Based on Convolutional and Recurrent Deep Neural Networks [[Paper](https://ieeexplore.ieee.org/document/8462049)]

* **[ICASSP'18]** A Simple Cepstral Domain DNN Approach to Artificial Speech Bandwidth Extension [[Paper](https://ieeexplore.ieee.org/document/8462362)]

* **[TASLP'18]** Waveform Modeling and Generation Using Hierarchical Recurrent Neural Networks for Speech Bandwidth Extension [[Paper](https://ieeexplore.ieee.org/document/8270683)]

* **[TASLP'18]** Artificial Speech Bandwidth Extension Using Deep Neural Networks for Wideband Spectral Envelope Estimation [[Paper](https://ieeexplore.ieee.org/document/8063328)]

* **[INTERSPEECH'17]** Waveform Modeling Using Stacked Dilated Convolutional Neural Networks for Speech Bandwidth Extension [[Paper](https://www.isca-archive.org/interspeech_2017/gu17_interspeech.html)]

* **[ICLR Workshop'17]** Audio Super Resolution using Neural Networks [[Paper](https://arxiv.org/abs/1708.00853)] [[Code](https://github.com/kuleshov/audio-super-res)]

* **[INTERSPEECH'16]** Speech Bandwidth Extension Using Bottleneck Features and Deep Recurrent Neural Networks [[Paper](https://www.isca-archive.org/interspeech_2016/gu16b_interspeech.html)]

* **[INTERSPEECH'16]** A Novel Research to Artificial Bandwidth Extension Based on Deep BLSTM Recurrent Neural Networks and Exemplar-Based Sparse Representation [[Paper](https://www.isca-archive.org/interspeech_2016/liu16k_interspeech.html)]

* **[IWAENC'16]** Artificial bandwidth extension using deep neural networks for spectral envelope estimation [[Paper](https://ieeexplore.ieee.org/document/7602894)]

* **[ICASSP'15]** A deep neural network approach to speech bandwidth expansion [[Paper](https://ieeexplore.ieee.org/document/7178801)]

* **[INTERSPEECH'15]** A Novel Method of Artificial Bandwidth Extension Using Deep Architecture [[Paper](https://www.isca-archive.org/interspeech_2015/liu15g_interspeech.html)]

* **[INTERSPEECH'15]** Speech bandwidth expansion based on deep neural networks [[Paper](https://www.isca-archive.org/interspeech_2015/wang15i_interspeech.html)]

* **[INTERSPEECH'15]** DNN-based speech bandwidth expansion and its application to adding high-frequency missing features for automatic speech recognition of narrowband speech [[Paper](https://www.isca-archive.org/interspeech_2015/li15d_interspeech.html)]

* **[IJCNN'15]** Restoring high frequency spectral envelopes using neural networks for speech bandwidth extension [[Paper](https://ieeexplore.ieee.org/document/7280483)]

---

## Transformers

### 2025

* **[arXiv'25]** A High-Fidelity Speech Super Resolution Network using a Complex Global Attention Module with Spectro-Temporal Loss [[Paper](https://arxiv.org/abs/2507.00229)]

* **[INTERSPEECH'25]** A Neural Codec Approach for Noise-Robust Bandwidth Expansion [[Paper](https://www.isca-archive.org/interspeech_2025/liu25p_interspeech.pdf)] [[Demo](https://winkee520.github.io/NRBWE/)]

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

### 2026

* **[ICASSP'26]** HCGAN: Harmonic-Coupled Generative Adversarial Network for Speech Super-Resolution in Low-Bandwidth Scenarios [[Paper](https://ieeexplore.ieee.org/document/11462170)]

* **[ICASSP'26]** NLDSI-BWE: Non Linear Dynamical Systems-Inspired Multi Resolution Discriminators for Speech Bandwidth Extension [[Paper](https://ieeexplore.ieee.org/document/11464384)]

* **[INTERSPEECH'26]** SEMamba++: A General Speech Restoration Framework Leveraging Global, Local, and Periodic Spectral Patterns [[Paper](https://arxiv.org/abs/2603.11669)] [[Code](https://github.com/infected4098/SEMambapp)] [[Demo](https://sites.google.com/view/semambapp)]

* **[TASLP'26]** A Harmonic-Coupled Generative Adversarial Network for Speech Super-Resolution in Low Bandwidth Scenarios [[Paper](https://ieeexplore.ieee.org/document/11447414)]

* **[TASLP'26]** EDNet: A Versatile Speech Enhancement Framework With Gating Mamba Mechanism and Phase Shift-Invariant Training [[Paper](https://ieeexplore.ieee.org/document/11373856)] [[Demo](https://mm.kaist.ac.kr/projects/EDNet/)]

* **[SPL'26]** Real-World Speech Recovery Under Multiple Distortions: A Two-Stage Framework With Feature Consistency and Adversarial Fine-Tuning [[Paper](https://ieeexplore.ieee.org/document/11368729)]

### 2025

* **[ICASSP'25]** HiFi-SR: A Unified Generative Transformer-Convolutional Adversarial Network for High-Fidelity Speech Super-Resolution [[Paper](https://ieeexplore.ieee.org/document/10888627)]

* **[ICASSP'25]** Wave-U-Mamba: An End-To-End Framework For High-Quality And Efficient Speech Super Resolution [[Paper](https://ieeexplore.ieee.org/document/10890511)] [[Code](https://github.com/infected4098/Wave-U-Mamba)]

* **[INTERSPEECH'25]** Frequency-Domain Enhanced Extreme Bandwidth Extension Network with ICCRN for Superior Speech Quality [[Paper](https://www.isca-archive.org/interspeech_2025/bao25_interspeech.html)]

* **[INTERSPEECH'25]** HWB-Net: A Novel High-Performance and Efficient Hybrid Waveform Bandwidth Extension Method [[Paper](https://www.isca-archive.org/interspeech_2025/liu25d_interspeech.html)]

* **[TASLP'25]** VM-ASR: A Lightweight Dual-Stream U-Net Model for Efficient Audio Super-Resolution [[Paper](https://ieeexplore.ieee.org/document/10852332)] [[Code](https://github.com/ghnmqdtg/vm-asr)] [[Demo](https://ghnmqdtg.github.io/vm-asr-demo/)]

* **[TASLP'25]** SFNet: A Two-Stage Source-Filter-Based Neural Network for Real-Time Speech Bandwidth Extension [[Paper](https://ieeexplore.ieee.org/document/11269710)]

* **[arXiv'25]** SwinSRGAN: Swin Transformer-based Generative Adversarial Network for High-Fidelity Speech Super-Resolution [[Paper](https://arxiv.org/html/2509.03913v3)]

### 2024

* **[ICASSP'24]** BAE-Net: a Low Complexity and High Fidelity Bandwidth-Adaptive Neural Network for Speech Super-Resolution [[Paper](https://ieeexplore.ieee.org/document/10446439)] [[Code](https://github.com/yuguochencuc/BAE-Net)]

* **[INTERSPEECH'24]** Multi-Stage Speech Bandwidth Extension with Flexible Sampling Rate Control [[Paper](https://www.isca-archive.org/interspeech_2024/lu24_interspeech.html)] [[Demo](https://yxlu-0102.github.io/MS-BWE-demo/)]

* **[TASLP'24]** Audio Super-Resolution With Robust Speech Representation Learning of Masked Autoencoder [[Paper](https://ieeexplore.ieee.org/document/10381805)] [[Code](https://github.com/FrePainter/code)] [[Demo](https://frepainter.github.io/demo/)]

* **[TASLP'24]** Towards High-Quality and Efficient Speech Bandwidth Extension With Parallel Amplitude and Phase Prediction [[Paper](https://ieeexplore.ieee.org/document/10806888)] [[Code](https://github.com/yxlu-0102/AP-BWE)] [[Demo](https://yxlu-0102.github.io/AP-BWE/)]

* **[TASLP'24]** Time-Domain Speech Super-Resolution With GAN Based Modeling for Telephony Speaker Verification [[Paper](https://ieeexplore.ieee.org/document/10444048)]

* **[JASA'24]** Spectral Network Based on Lattice Convolution and Adversarial Training for Noise-Robust Speech Super-Resolution (SDNet) [[Paper](https://pubs.aip.org/asa/jasa/article/156/5/3143/3320008)]

### 2023

* **[ICASSP'23]** EBEN: Extreme Bandwidth Extension Network Applied To Speech Signals Captured With Noise-Resilient Body-Conduction Microphones [[Paper](https://ieeexplore.ieee.org/document/10096301)] [[Code](https://github.com/jhauret/eben)] [[Demo](https://jhauret.github.io/eben/)]

* **[ICASSP'23]** Nonparallel High-Quality Audio Super Resolution with Domain Adaptation and Resampling CycleGANs [[Paper](https://ieeexplore.ieee.org/document/10097002)] [[Code](https://github.com/chomeyama/DualCycleGAN)] [[Demo](https://chomeyama.github.io/DualCycleGAN-Demo/)]

* **[ICASSP'23]** HIFI++: A Unified Framework for Bandwidth Extension and Speech Enhancement [[Paper](https://ieeexplore.ieee.org/document/10097255)]

* **[INTERSPEECH'23]** mdctGAN: Taming transformer-based GAN for speech super-resolution with Modified DCT spectra [[Paper](https://www.isca-archive.org/interspeech_2023/shuai23_interspeech.html)] [[Code](https://github.com/neoncloud/mdctGAN)]

* **[EUSIPCO'23]** Low-Complexity Real-Time Neural Network for Blind Bandwidth Extension of Wideband Speech [[Paper](https://ieeexplore.ieee.org/document/10290072)] [[Demo](https://eagomez2.github.io/bbwexnet/)]

* **[MLSP'23]** Low-Complexity Streaming Speech Super-Resolution [[Paper](https://ieeexplore.ieee.org/document/10285965)]

### Earlier Works

* **[INTERSPEECH'22]** Neural Vocoder is All You Need for Speech Super-resolution [[Paper](https://www.isca-archive.org/interspeech_2022/liu22x_interspeech.pdf)] [[Demo](https://haoheliu.github.io/haoheliu_prev_profile/nvsr)]

* **[INTERSPEECH'22]** VoiceFixer: A Unified Framework for High-Fidelity Speech Restoration [[Paper](https://www.isca-archive.org/interspeech_2022/liu22y_interspeech.html)] [[Code](https://github.com/haoheliu/voicefixer)]

* **[TASLP'22]** BEHM-GAN: Bandwidth Extension of Historical Music Using Generative Adversarial Networks [[Paper](https://ieeexplore.ieee.org/document/9829821)] [[Code](https://github.com/eloimoliner/bwe_historical_recordings)]

* **[ICASSP'21]** Real-Time Speech Frequency Bandwidth Extension [[Paper](https://ieeexplore.ieee.org/document/9413439)]

* **[ICASSP'21]** Bandwidth Extension is All You Need [[Paper](https://ieeexplore.ieee.org/document/9413575)] [[Demo](https://pixl.cs.princeton.edu/pubs/Su_2021_BEI/)]

* **[ICASSP'20]** Time-Domain Neural Network Approach for Speech Bandwidth Extension [[Paper](https://ieeexplore.ieee.org/document/9054551)]

* **[ICASSP'19]** Speech Super Resolution Generative Adversarial Network [[Paper](https://ieeexplore.ieee.org/document/8682215)]

* **[ICASSP'19]** Cyclegan Bandwidth Extension Acoustic Modeling for Automatic Speech Recognition [[Paper](https://ieeexplore.ieee.org/document/8682760)]

* **[ICASSP'19]** Artificial Bandwidth Extension Using a Conditional Generative Adversarial Network with Discriminative Training [[Paper](https://ieeexplore.ieee.org/document/8682649)]

* **[INTERSPEECH'19]** Speech Audio Super-Resolution for Speech Recognition [[Paper](https://www.isca-archive.org/interspeech_2019/li19q_interspeech.html)]

* **[arXiv'19]** Bandwidth Extension on Raw Audio via Generative Adversarial Networks [[Paper](https://arxiv.org/abs/1903.09027)]

* **[ICASSP'18]** Speech Bandwidth Extension Using Generative Adversarial Networks [[Paper](https://ieeexplore.ieee.org/document/8462588)]
  
---

## Diffusion

### 2026
* **[arXiv'26]** FastWave: Optimized Diffusion Model for Audio Super-Resolution [[Paper](https://arxiv.org/abs/2603.04122)] [[Code](https://github.com/Nikait/FastWave)]

* **[AAAI'26]** Inference-time Scaling for Diffusion-based Audio Super-resolution [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/38520)] [[Demo](https://racerk.github.io/tt-scale-audiosr/)]

### 2025

* **[ICASSP'25]** FlashSR: One-step Versatile Audio Super-resolution via Diffusion Distillation [[Paper](https://ieeexplore.ieee.org/document/10889472)] [[Demo](https://jakeoneijk.github.io/flashsr-demo/)]

* **[ICASSP'25]** Vector Quantized Diffusion Model Based Speech Bandwidth Extension [[Paper](https://ieeexplore.ieee.org/document/10889180)] 

### 2024

* **[ICASSP'24]** Audiosr: Versatile Audio Super-Resolution at Scale [[Paper](https://ieeexplore.ieee.org/document/10447246)] [[Code](https://github.com/haoheliu/versatile_audio_super_resolution)]

* **[INTERSPEECH'24]** A Parameterized Stochastic Diffusion Process for Noise-Robust Bandwidth Expansion [[Paper](https://www.isca-archive.org/interspeech_2024/lin24c_interspeech.pdf)] [[Code](https://github.com/alexlinander/SWiBE)]

* **[INTERSPEECH'24]** UNIVERSE++: Universal Score-based Speech Enhancement with High Content Preservation [[Paper](https://www.isca-archive.org/interspeech_2024/scheibler24_interspeech.html)] [[Code](https://github.com/line/open-universe)] [[Demo](https://www.robinscheibler.org/interspeech2024-universepp-samples/)]

* **[TASLP'24]** Blind Audio Bandwidth Extension: A Diffusion-Based Zero-Shot Approach [[Paper](https://ieeexplore.ieee.org/document/10768977)] [[Code](https://github.com/eloimoliner/BABE)]

### 2023

* **[ICASSP'23]** Conditioning and Sampling in Variational Diffusion Models for Speech Super-Resolution (UDM+) [[Paper](https://ieeexplore.ieee.org/document/10095103)] [[Code](https://github.com/iamycy/diffwave-sr)] [[Demo](https://iamycy.github.io/diffwave-sr/)]

* **[ICASSP'23]** Analysing Diffusion-based Generative Approaches Versus Discriminative Approaches for Speech Restoration [[Paper](https://ieeexplore.ieee.org/document/10095258)] [[Code](https://github.com/sp-uhh/sgmse)]

### Earlier Works

* **[arXiv'22]** Universal Speech Enhancement with Score-based Diffusion (UNIVERSE) [[Paper](https://arxiv.org/abs/2206.03065)] [[Demo](https://serrjoa.github.io/projects/universe/)]

* **[INTERSPEECH'22]** NU-Wave 2: A General Neural Audio Upsampling Model for Various Sampling Rates [[Paper](https://www.isca-archive.org/interspeech_2022/han22_interspeech.html)] [[Code](https://github.com/maum-ai/nuwave2)]

* **[INTERSPEECH'21]** NU-Wave: A Diffusion Probabilistic Model for Neural Audio Upsampling [[Paper](https://www.isca-archive.org/interspeech_2021/lee21c_interspeech.html)] [[Code](https://github.com/maum-ai/nuwave)]

---

## Flow

### 2026

* **[arXiv'26]** LatentFlowSR: High-Fidelity Audio Super-Resolution via Noise-Robust Latent Flow Matching [[Paper](https://arxiv.org/abs/2604.09188)]

* **[arXiv'26]** CodecFlow: Efficient Bandwidth Extension via Conditional Flow Matching in Neural Codec Latent Space [[Paper](https://arxiv.org/abs/2603.02022)]

* **[ICASSP'26]** Universr: Unified and Versatile Audio Super-Resolution Via Vocoder-Free Flow Matching [[Paper](https://ieeexplore.ieee.org/document/11460830)] [[Code](https://github.com/woongzip1/UniverSR)]

* **[ICASSP'26]** SAGA-SR: Semantically and Acoustically Guided Audio Super-Resolution [[Paper](https://ieeexplore.ieee.org/document/11460886)] [[Code](https://github.com/jakeoneijk/SAGA-SR)]

* **[ICASSP'26]** Towards Real-Time Generative Speech Restoration with Flow-Matching [[Paper](https://ieeexplore.ieee.org/document/11463015)]

* **[ICASSP'26]** Single-Step Controllable Music Bandwidth extension with Flow Matching [[Paper](https://ieeexplore.ieee.org/document/11461402)]


### 2025

* **[ICASSP'25]** FLowHigh: Towards Efficient and High-Quality Audio Super-Resolution with Single-Step Flow Matching [[Paper](https://ieeexplore.ieee.org/document/10888772)] [[Code](https://github.com/jjunak-yun/FLowHigh_code)]

* **[ICASSP'25]** Generative Speech Foundation Model Pretraining for High-Quality Speech Extraction and Restoration [[Paper](https://ieeexplore.ieee.org/document/10888830)] [[Demo](https://kuray107.github.io/ssl_gen25-examples/index.html)]

* **[TASLP'25]** Real-Time Streamable Generative Speech Restoration With Flow Matching [[Paper](https://ieeexplore.ieee.org/document/11533884)] [[Code](https://github.com/sp-uhh/streamfm)]

### Earlier Works
* **[INTERSPEECH'21]** WSRGlow: A Glow-Based Waveform Generative Model for Audio Super-Resolution [[Paper](https://www.isca-archive.org/interspeech_2021/zhang21k_interspeech.html)] [[Code](https://github.com/zkx06111/WSRGlow)]

---

## Schrödinger Bridge

### 2025

* **[NeurIPS'25]** Audio Super-Resolution with Latent Bridge Models [[Paper](https://papers.neurips.cc/paper_files/paper/2025/file/4572bc2f514e627914cbe60d0398a2d1-Paper-Conference.pdf)] [[Demo](https://audiolbm.github.io/?ref=aiartweekly)]

* **[ICASSP'25]** Bridge-SR: Schrödinger Bridge for Efficient SR [[Paper](https://ieeexplore.ieee.org/document/10890104)]

* **[arXiv'25]** A2SB: Audio-to-Audio Schrodinger Bridges [[Paper](https://arxiv.org/abs/2501.11311)] [[Code](https://github.com/NVIDIA/diffusion-audio-restoration)]

---
