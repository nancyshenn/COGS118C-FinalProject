# 🧠 EEG Signal Analysis: Control vs Alzheimer’s Disease

![Python](https://img.shields.io/badge/Python-3.9+-blue)
![NumPy](https://img.shields.io/badge/NumPy-Used-orange)
![Pandas](https://img.shields.io/badge/Pandas-Used-purple)
![Matplotlib](https://img.shields.io/badge/Visualization-Matplotlib-green)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

## 📌 Overview
This project explores differences in brain activity between **healthy (Control)** subjects and individuals with **Alzheimer’s Disease (AD)** using EEG (Electroencephalography) data.

Through signal processing and statistical analysis, we investigate how neural activity patterns differ between the two groups, with a focus on:
- Signal structure and variability  
- Noise reduction and preprocessing  
- Temporal patterns and smoothing  
- Distribution differences  
- Functional connectivity between brain regions  

---

## 🎯 Objectives
- Compare raw and processed EEG signals between Control and AD subjects  
- Identify distinguishing signal characteristics (amplitude, variability, irregularity)  
- Analyze synchronization between brain regions using cross-correlation  
- Explore whether EEG features can act as potential biomarkers for Alzheimer’s Disease  

---

## 📊 Results at a Glance

- 📉 **Higher Variability in AD:** EEG signals from AD subjects show greater amplitude spread and irregular fluctuations  
- 🔗 **Reduced Connectivity:** Cross-correlation analysis reveals weaker synchronization between brain regions in AD  
- 📊 **Distribution Differences:** AD signals exhibit wider distributions with heavier tails  
- 📈 **Less Stable Trends:** Smoothed signals (rolling mean) show less consistent patterns in AD compared to Control  
- ⚡ **Persistent Noise/Irregularity:** Even after preprocessing, AD signals remain more chaotic  

👉 These patterns suggest **neural degradation and reduced coordination**, supporting EEG as a potential diagnostic signal for Alzheimer’s Disease.

---

## 📊 Key Analyses

### 1. Raw Signal Visualization
- Plotted EEG signals from multiple channels  
- Compared Control vs AD over time  
- Observed differences in amplitude and irregularity  

### 2. Processed Signal Analysis
- Applied preprocessing techniques (e.g., filtering, normalization)  
- Reduced noise and improved comparability  
- AD signals remained more irregular even after processing  

### 3. Rolling Mean & Smoothing
- Applied rolling mean (window size = 100)  
- Highlighted underlying trends in EEG signals  
- Control signals appeared more stable and structured  

### 4. Distribution Comparison (Histograms)
- Compared amplitude distributions across channels  
- AD signals showed:
  - Wider spread  
  - Heavier tails  
  - Greater variability  

### 5. Cross-Correlation Analysis
- Measured synchronization between EEG channels  
- Findings:
  - **Control:** Stronger, structured correlations  
  - **AD:** Weaker, less predictable correlations  
- Suggests reduced neural connectivity in AD  

### 6. Spectrogram Analysis
- Explored frequency-domain characteristics of EEG signals  
- Compared time-frequency patterns between Control and AD  

---

## 🧪 Key Insights
- AD EEG signals tend to be **more irregular and less synchronized**  
- **Amplitude variability** is higher in AD subjects  
- **Cross-channel connectivity** is weaker in AD  
- These differences align with known effects of neurodegeneration  

👉 Overall, EEG signal characteristics show potential as **biomarkers for Alzheimer’s Disease detection**

---

## 🗂️ Project Structure

```
eeg-ad-analysis/
├── data/                          # Raw and processed EEG datasets  
│   ├── Control_EEG_sub_037.npy  
│   ├── Control_EEG_sub_037_processed.npy  
│   ├── AD_EEG_sub_001.npy  
│   └── AD_EEG_sub_001_processed.npy  
│
├── final_proj.ipynb               # Main analysis notebook  
└── README.md                     # Project documentation
```
---

## ⚙️ Technologies Used
- Python  
- NumPy  
- Pandas  
- Matplotlib  
- SciPy  

---

## 📚 References
https://www.mdpi.com/2306-5729/8/6/95  
https://github.com/hengxu19/COGS118C

