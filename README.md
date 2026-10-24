<h1 align="center">🎤 Text-to-Speech Using My Voice</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white"/>
  <img src="https://img.shields.io/badge/Voice-Cloning-00b39e?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/TTS-Custom%20Voice-412991?style=for-the-badge"/>
</p>

<p align="center">
  A personal voice cloning project — training a TTS model on custom voice recordings
  to synthesize speech that sounds like the speaker's own voice.
</p>

---

## 🎯 What It Does

Records → trains → synthesizes. Given a few minutes of your own voice recordings, the model learns your vocal characteristics and can generate new speech in your voice from any text input.

---

## 🏗️ Pipeline

```
Personal Voice Recordings (WAV/MP3)
        │
        ▼
Audio Preprocessing
(normalization, silence trimming, alignment)
        │
        ▼
Speaker Encoder
(extract voice embedding from recordings)
        │
        ▼
TTS Model Training
(fine-tune on personal voice data)
        │
        ▼
Text Input → Mel-Spectrogram → Vocoder
        │
        ▼
🔊 Synthesized speech in your voice
```

---

## ✨ Features

- **Personal voice cloning** — train on your own recordings
- **Custom TTS** — not a pre-trained generic voice
- **Flexible input** — synthesize any text after training
- **Jupyter-based** — easy to follow, step-by-step notebook

---

## 🔗 Related Research

This project uses architectures documented in:
→ [R-D-about-TTS-Models-Architecture-Structure](https://github.com/Ramisa-16/R-D-about-TTS-Models-Architecture-Structure)

---

## 🚀 Getting Started

```bash
git clone https://github.com/Ramisa-16/Text-to-Speech-using-My-voice.git
cd Text-to-Speech-using-My-voice
pip install -r requirements.txt
jupyter notebook
```

---

## 🛠️ Tech Stack

**Python** · **Jupyter Notebook** · **TTS Libraries** · **PyTorch** · **Librosa**

---

## 👩‍💻 Author

**Ramisa Sharar Nidhi** — AI Developer @ Betopia Group
[![LinkedIn](https://img.shields.io/badge/LinkedIn-ramisashararnidhi-0077B5?style=flat&logo=linkedin)](https://linkedin.com/in/ramisashararnidhi)
[![GitHub](https://img.shields.io/badge/GitHub-Ramisa--16-181717?style=flat&logo=github)](https://github.com/Ramisa-16)
