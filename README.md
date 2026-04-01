# 🧠 Parkinson’s Disease Detection using Handwriting Analysis

## 📌 Description
This project is an AI-based system designed to detect Parkinson’s disease using handwriting images such as spiral and wave drawings.

Parkinson’s disease affects motor skills, and one of the early symptoms appears in handwriting patterns. This system analyzes those patterns using a combination of deep learning and handcrafted feature extraction techniques.

---

## ⚙️ How It Works

### 1. Input
- Handwritten images (spiral or wave drawings)

### 2. Feature Extraction
The system extracts multiple types of features:

- **Deep Features (EfficientNet)**  
  Captures complex visual patterns like distortions and irregular shapes  

- **Texture Features (GLCM)**  
  Measures smoothness, consistency, and irregularity  

- **Edge Features**  
  Detects shaky or broken strokes  

- **Frequency Features (FFT)**  
  Identifies tremor-related patterns  

---

### 3. Feature Fusion
All extracted features are combined into a single feature vector to improve model performance.

---

### 4. Classification
Machine learning models such as Gradient Boosting, SVM, and ensemble methods are used to classify the input as:

- ✅ Healthy  
- ❌ Parkinson’s  

---

### 5. Output
- Disease prediction  
- Probability score  
- Performance metrics (accuracy, AUC, etc.)

---

## 🎯 Objective
- Enable early detection of Parkinson’s disease  
- Provide a non-invasive and low-cost screening method  
- Support healthcare professionals using AI  

---

## 🚀 Applications
- Medical screening tools  
- Telemedicine platforms  
- AI-powered healthcare systems  
- Assistive diagnostic support  

---

## 💡 Key Features
- Hybrid feature extraction (Deep + Handcrafted)  
- Feature fusion approach  
- Ensemble learning models  
- Explainable AI capability (Grad-CAM)  

---

## 📊 Result Summary
The model demonstrates the ability to distinguish between healthy and Parkinson’s handwriting patterns, achieving moderate accuracy and showing potential for further improvement with larger datasets.

---

## 📌 Future Scope
- Improve accuracy with larger datasets  
- Deploy as a web or mobile application  
- Integrate real-time handwriting input  
- Enhance clinical validation  

---

## 👩‍💻 Author
**M. Nivetha**  
B.Tech Artificial Intelligence and Machine Learning  

---

## 📜 License
This project is intended for academic and research purposes.
