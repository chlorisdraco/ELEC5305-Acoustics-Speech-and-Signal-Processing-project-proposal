# ELEC5305-Acoustics-Speech-and-Signal-Processing-project-proposal
A project proposal for ELEC5305 – focusing on  Audio Processing 
# <span style="color:#1E90FF">ELEC5305 Acoustics, Speech and Signal Processing</span>  

<img src="https://upload.wikimedia.org/wikipedia/en/7/71/University_of_Sydney_coat_of_arms.png" alt="USYD Logo" width="120"/>  

**Author:** Jiahao Xu  
**SID:** 530332675  
**Date:** 31/08/2025  

---

## <span style="color:#FF4500">Objective</span>  
The purpose of this project proposal is to demonstrate **basic audio signal processing in MATLAB** through the analysis of both speech and music signals.  
The work includes:  
- Operations in the time domain and frequency domain  
- The synthesis of a bell sound using decaying sinusoids  
- Extraction of short-time features such as energy, zero-crossing rate, and spectral measures  
- Comparison between speech and music signals  
- Application of narrowband and wideband short-time Fourier transforms (STFT)  

---

## <span style="color:#2E8B57">Background / Introduction</span>  
Audio signals contain useful information in both the **time domain** and **frequency domain**.  

- **Speech**: Often has strong energy below 4 kHz.  
- **Music**: Usually shows wider frequency content.  

Short-time features include:  
- **Energy** → Loudness  
- **Zero-crossing rate** → Linked with noisiness  
- **Spectral centroid & bandwidth** → Distribution of spectral energy  
- **Spectral flux & rolloff** → Capture changes in the spectrum  

The **short-time Fourier transform (STFT)** is applied to non-stationary signals to balance **time resolution vs frequency resolution**.

---

## <span style="color:#8A2BE2">Methodology / Implementation</span>  
The project is divided into **five main parts**:  

1. Load music and speech signals, convert to mono, segment into 15-second portions, and plot in time domain.  
2. Perform time and frequency analysis using **FFT**.  
3. Synthesize a bell sound from decaying sinusoids.  
4. Extract short-time features (energy, zero-crossing rate, spectral centroid, bandwidth, flux, rolloff).  
5. Apply **narrowband vs wideband STFT** to compare time-frequency trade-offs.  

---

## <span style="color:#DAA520">Discussion</span>  
- Speech signals: Strong low-frequency components, concentrated below 4 kHz.  
- Music signals: Broader frequency range, richer high-frequency details.  
- STFT analysis: Narrowband provides better frequency detail, while wideband improves time localisation.  

---

## <span style="color:#4682B4">References</span>  
- Rabiner, L. & Schafer, R. (2011). *Theory and Applications of Digital Speech Processing*. Pearson.  
- Lyons, R. (2010). *Understanding Digital Signal Processing*. Prentice Hall.  
- Smith, J.O. (2007). *Introduction to Digital Filters with Audio Applications*. W3K Publishing.  
