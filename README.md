**Author:** Jiahao Xu  
**SID:** 530332675  
**Date:** 31/08/2025  

---

## Objective
The purpose of this project proposal is to demonstrate **basic audio signal processing in MATLAB** through the analysis of both speech and music signals.  

The work includes:
Operations in the time and frequency domain  
Synthesis of a bell sound using decaying sinusoids  
Extraction of short-time features such as energy, zero-crossing rate, and spectral measures  
Comparison between speech and music signals  
Application of narrowband and wideband short-time Fourier transforms (STFT)  

---

## Background / Introduction
Audio signals contain useful information in both the **time domain** and **frequency domain**.  

**Speech**: Strong energy typically below 4 kHz  
**Music**: Wider frequency content  

Short-time features:  
Energy → Related to loudness  
Zero-crossing rate → Linked to noisiness  
Spectral centroid & bandwidth → Distribution of spectral energy  
Spectral flux & rolloff → Spectrum changes  

The **short-time Fourier transform (STFT)** addresses the trade-off between **time resolution** and **frequency resolution**.

---

## Methodology / Implementation
The project is divided into **five main parts**:

1. Load and preprocess signals (music & speech), convert to mono, segment into 15 s portions.  
2. Perform time and frequency analysis using **FFT**.  
3. Synthesize a bell sound using decaying sinusoids.  
4. Extract short-time features (energy, zero-crossing rate, spectral centroid, bandwidth, flux, rolloff).  
5. Compare narrowband vs wideband spectrograms using **STFT**.  

---

## Discussion
**Speech signals**: Strong low-frequency components (< 4 kHz).  
**Music signals**: Wider frequency content with richer high-frequency details.  
**STFT**: Narrowband → better frequency detail; Wideband → better time localisation.  

---

## References
Rabiner, L. & Schafer, R. (2011). *Theory and Applications of Digital Speech Processing*. Pearson.  
Lyons, R. (2010). *Understanding Digital Signal Processing*. Prentice Hall.  
Smith, J.O. (2007). *Introduction to Digital Filters with Audio Applications*. W3K Publishing.  

---
## GitHub project site
https://chlorisdraco.github.io/ELEC5305-Acoustics-Speech-and-Signal-Processing-project-proposal/
