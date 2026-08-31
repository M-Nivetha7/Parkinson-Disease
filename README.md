# Parkinson's Disease Detection and Severity Prediction Using Machine Learning

A machine learning research project focused on the detection and severity prediction of Parkinson's Disease using **voice, handwriting, and biomedical biomarkers**.

The repository contains multiple Jupyter Notebooks exploring different machine learning approaches for Parkinson's Disease analysis, including voice-based detection, voice-based severity prediction, and handwriting-based detection.

---

![Uploading Screenshot 2026-08-31 at 6.48.31 PM.png…]()



---

[Machine-Learning-Approaches-For-Parkinson-s-Disease-Detection-And-Severity-Prediction-Using-Voice-Biomarkers--A-Comprehensive-Analysis.pdf](https://github.com/user-attachments/files/31646545/Machine-Learning-Approaches-For-Parkinson-s-Disease-Detection-And-Severity-Prediction-Using-Voice-Biomarkers--A-Comprehensive-Analysis.pdf)

---


## 📌 Project Overview

Parkinson's Disease (PD) is a progressive neurological disorder that affects movement, speech, handwriting, and other motor functions.

Early detection and continuous assessment of Parkinson's Disease can support clinical decision-making and patient monitoring. Machine learning provides an opportunity to analyze non-invasive biomarkers such as:

- 🎙️ Voice and speech characteristics
- ✍️ Handwriting and drawing patterns
- 📊 Biomedical measurements
- 📈 Motor and total UPDRS scores

This project investigates machine learning techniques for:

1. **Parkinson's Disease detection**
2. **Parkinson's Disease severity prediction**
3. **Handwriting-based Parkinson's detection**
4. **Voice-based Parkinson's analysis**
5. **Comparison of machine learning models**
6. **Feature analysis and model evaluation**

---

## 🎯 Objectives

The main objectives of this project are:

- To investigate machine learning methods for Parkinson's Disease detection.
- To analyze voice-based biomarkers associated with Parkinson's Disease.
- To investigate handwriting characteristics for Parkinson's Disease detection.
- To predict Parkinson's Disease severity using voice measurements and UPDRS scores.
- To preprocess and analyze biomedical datasets.
- To compare different machine learning algorithms.
- To evaluate models using appropriate performance metrics.
- To identify important features contributing to Parkinson's Disease prediction.
- To develop a reproducible machine learning research workflow.

---

## 🧠 Research Areas

The project is divided into three major analysis areas.

### 1. Voice-Based Parkinson's Disease Detection

The voice-based detection task uses biomedical voice measurements to classify individuals into:

- `0` → Healthy
- `1` → Parkinson's Disease

The analysis includes acoustic features such as:

- Fundamental frequency
- Jitter
- Shimmer
- Noise-to-harmonics ratio
- Harmonics-to-noise ratio
- Recurrence measures
- Nonlinear dynamic features

---

### 2. Voice-Based Parkinson's Disease Severity Prediction

The project also investigates the prediction of Parkinson's Disease severity using voice measurements.

The **Parkinson's Telemonitoring Dataset** contains clinical severity measurements including:

- `motor_UPDRS`
- `total_UPDRS`

These measurements can be used as regression targets for estimating disease severity from voice characteristics.

---

### 3. Handwriting-Based Parkinson's Disease Detection

Handwriting is another important non-invasive biomarker for Parkinson's Disease.

The handwriting component investigates patterns in spiral/drawing images and explores machine learning or image-processing techniques for distinguishing Parkinson's Disease patients from healthy individuals.

Potentially relevant characteristics include:

- Tremor
- Stroke irregularity
- Spiral deformation
- Movement consistency
- Drawing patterns

---

# 📂 Repository Structure

```text
Parkinson-Disease/
│
├── Handwriting_based_Parkinson_detection.ipynb
│
├── Voice_based_Parkinson_severity_prediction.ipynb
│
├── Parkinson (1).ipynb
│
├── parkinsons.data
│
├── parkinsons+telemonitoring.zip
│
├── README.md
```


