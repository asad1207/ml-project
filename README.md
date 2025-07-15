# 📊 Substance Detecting using Machine Learning

This project implements a machine learning pipeline to classify or detect substance use patterns using image data — particularly facial images. It uses a combination of computer vision and classification models (e.g., CNNs, XGBoost) to predict potential drug use from visual input.

---

## 🚀 Project Overview

Substance abuse disorders are a growing global concern. Traditional methods for detecting such disorders are time-consuming and require human intervention. This notebook explores the use of **facial features** and **machine learning models** to detect possible **People with Drug Use Disorders (PDUD)**, using a dataset of facial images.

---

## 📁 Folder Structure

```
Substance-Detecting-ML/
│
├── Substance Detecting using ML.ipynb   # Main notebook
├── README.md                            # Project description
├── /data/                               # Training and test image data
├── /models/                             # Saved ML models (if any)
└── requirements.txt                     # Python dependencies
```

---

## 🧠 Models Used

- **Convolutional Neural Network (CNN)** for feature extraction
- **XGBoost** or other classifiers for final prediction
- Options for hybrid approaches combining CNN + classical ML models

---

## 🛠️ Technologies

- Python 🐍
- Google Colab / Jupyter Notebook
- TensorFlow / Keras
- OpenCV
- Scikit-learn
- XGBoost
- NumPy, Pandas, Matplotlib

---

## ⚙️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Substance-Detecting-ML.git
   cd Substance-Detecting-ML
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:
   - Open `Substance Detecting using ML.ipynb` in Jupyter/Colab.
   - Upload dataset if not already provided.
   - Run each cell sequentially.

---

## 🧪 Dataset Info

- Facial image dataset categorized into:
  - **PDUD (People with Drug Use Disorders)**
  - **GP (General Population)**

> *Dataset not included due to size/privacy. Please refer to notebook instructions for upload.*

---

## 📈 Results

The model achieved satisfactory accuracy in classifying facial images into PDUD or GP using various techniques including:
- Image preprocessing
- Feature reduction
- Transfer learning (e.g., FaceNet, ArcFace - optional)

---

## 📌 Future Work

- Integrate with real-time webcam input
- Expand to multi-class classification (types of substance)
- Improve robustness with larger, balanced datasets

---

## 🧑‍💻 Author

- **Asad Ghouse**  
  *B.Tech CSE, Data Science Enthusiast*

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
