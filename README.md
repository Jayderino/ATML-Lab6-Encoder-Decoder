# 🚀 ATML Lab 6 — Encoder-Decoder Architecture

## 📌 Overview

This project implements an **Encoder-Decoder (Seq2Seq) architecture using LSTM** for:

* English → Hindi Machine Translation
* English → Spanish Machine Translation
* Next Word Prediction
* Interactive Gradio UI

---

## 🧠 Model Architecture

* Encoder: Multi-layer LSTM
* Decoder: Multi-layer LSTM
* Teacher Forcing
* Gradient Clipping

---

## ⚙️ Hyperparameters

| Parameter     | Value |
| ------------- | ----- |
| Embedding Dim | 256   |
| Hidden Dim    | 512   |
| Layers        | 2     |
| Batch Size    | 64    |
| Epochs        | 30    |

---

## 📊 Results

### 🔹 Training Curve

![Training Curve](lab6_training_curve.png)

### 🔹 Translation Output

![Translation](translation_output.png)

---

## 🖥️ Gradio UI — Next Word Predictor

### 🔹 UI Example 1

![UI1](gradio_ui1.png)

### 🔹 UI Example 2

![UI2](gradio_ui2.png)

### 🔹 UI Example 3

![UI3](gradio_ui3.png)

### 🔹 UI Example 4

![UI4](gradio_ui4.png)

---

## 🌍 Tasks Implemented

* English → Hindi Translation
* BLEU Score Evaluation
* English → Spanish Translation
* Next Word Predictor

---

## 🖥️ How to Run

1. Open notebook in Google Colab
2. Enable GPU (T4)
3. Run all cells
4. Launch Gradio

---

## 👨‍💻 Author

* Jaden Castelino
* NMIMS Mumbai
