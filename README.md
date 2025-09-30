# 🎙️ Speech Emotion Recognition (SER) with Streamlit  

## 📌 Project Overview  
This project focuses on building a machine learning system that can recognize human emotions from speech.  
Using **audio feature extraction** (MFCCs, chroma, spectral features) and **machine learning models**, the system predicts emotions such as happiness, sadness, anger, and neutrality.  

To make the solution interactive, the project is **deployed as a Streamlit web application** where users can upload audio files and receive real-time emotion predictions.  

---

## 🚀 Features  
- Extracts features from audio using **Librosa**  
- Trains multiple classifiers (Logistic Regression, Random Forest, SVM)  
- Evaluates models with accuracy, confusion matrix, and F1-score  
- Interactive **Streamlit app** for real-time emotion recognition  
- Deployed on **Streamlit Cloud**  

---

## 🛠️ Tech Stack  
- **Programming Language:** Python  
- **Libraries:** Librosa, NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn  
- **Deployment:** Streamlit, Streamlit Cloud  
- **Version Control:** Git & GitHub  

---

## 📂 Project Structure  
```bash
├── data/                 # Audio dataset (not included in repo due to size)
├── notebooks/
│   ├── Speech_Emotion_Recognition.ipynb       # Training and evaluation
│   └── Speech_Emotion_Recognition_Deploy.ipynb # Streamlit deployment notebook
├── app.py                # Streamlit app script
├── README.md             # Project documentation
```

---

## ⚙️ Installation & Setup  

1. **Clone the repository**  
```bash
git clone https://github.com/yourusername/speech-emotion-recognition.git
cd speech-emotion-recognition
```

2. **Run the Streamlit app**  
```bash
streamlit run app.py
```

---

## 🎮 Usage  
1. Open the app in your browser.  
2. Upload an audio file.  
3. View the predicted emotion in real-time.  

---

## 📊 Results  
- Best-performing model: **Random Forest Classifier**  
- Accuracy: **XX%** (replace with your actual result)  
- Insights: MFCC features contributed most to emotion classification.  

---


