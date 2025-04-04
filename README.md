# 🎙️ Speech Emotion Recognition using MLP Classifier

This project implements **Speech Emotion Recognition (SER)** using **Mel-frequency cepstral coefficients (MFCC)** as features and an **MLPClassifier** for emotion classification. The goal is to automatically recognize human emotions from audio recordings using machine learning.

---

## 📌 Objective

To build a model that can classify emotions from speech using audio features and machine learning algorithms.

---

## 📁 Dataset

- **Source**: [RAVDESS Dataset](https://www.kaggle.com/uwrfkaggler/ravdess-emotional-speech-audio)
- **Description**: A speech emotion dataset consisting of 7356 files in `.wav` format, covering 8 emotions:
  - Neutral
  - Calm
  - Happy
  - Sad
  - Angry
  - Fearful
  - Disgust
  - Surprised

---

## ⚙️ Features Extracted

- **MFCC (Mel Frequency Cepstral Coefficients)**  
Used to convert audio signals into a fixed-length feature vector for each audio file.

---

## 🧠 Model

- **Algorithm**: Multi-Layer Perceptron (MLP) Classifier
- **Library**: Scikit-learn

### Model Parameters:
- `hidden_layer_sizes=(100,)`
- `activation='relu'`
- `solver='adam'`
- `learning_rate='constant'`

---

## 🧪 Evaluation

- **Accuracy Achieved**: ~83.6%
- **Train-Test Split**: 80-20
- **Confusion Matrix**: Used to analyze emotion-wise performance

---

## 📊 Visualization

- Bar graphs for emotion distribution
- Confusion matrix heatmap

---

## 📚 Requirements

```bash
pip install librosa scikit-learn matplotlib pandas numpy
