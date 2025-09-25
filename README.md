# 🎶 Signal Processing Project

## 📘 Overview

This is a simple Python project for generating, analyzing, and filtering audio signals.
It demonstrates how to **create a sound signal**, **add noise**, and **clean it back** using **FFT (Fast Fourier Transform)**.
The project not only shows plots and figures, but also **plays real audio** so you can **hear the difference** between the original, noisy, and filtered signals.

---

## 📂 Project Structure

```
.
├── signals.py           # Main Python script
├── requirements.txt  # Required Python libraries
└── figures/          # Plots and results (time & frequency domain)
```

---

## ▶️ How to Run

1. Install the required libraries:

```bash
pip install -r requirements.txt
```

2. Run the project:

```bash
python main.py
```

---

## 🧠 What It Does

* 🎵 **Generates** a musical signal made of multiple piano notes
* 🔊 **Plays** the original sound so you can hear the generated melody
* 📡 **Adds noise** and plays the noisy signal to simulate real-world interference
* 🧹 **Removes noise** using FFT filtering and plays the **cleaned version** of the sound
* 📈 **Plots** time-domain and frequency-domain graphs before and after filtering

---

## 📊 Output

* Original signal (time & frequency) + ✅ clean audio
* Noisy signal (time & frequency) + 🔉 noisy audio
* Filtered signal (time & frequency) + 🎧 restored audio

---

✅ This project gives both **visual** and **auditory** insight into how signal processing works — you can **see** the effect of noise in the plots and **hear** the improvement after filtering.
