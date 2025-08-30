# Mental Health Disorder Prediction using Machine Learning & Explainable AI  

This project leverages **Machine Learning (ML)** and **Explainable AI (XAI)** to predict different types of mental health disorders using structured survey data. The system aims to provide **accurate predictions** while maintaining **transparency and interpretability** for clinicians and patients.  

---

## Features  

- **Multi-disorder classification** (not just general detection, but distinguishing between disorders).  
- **Balanced dataset** using SMOTE to handle class imbalance.  
- **Models implemented**:  
  - Logistic Regression  
  - Random Forest  
  - Decision Tree  
- **Explainable AI (XAI) techniques**:  
  - SHAP (Shapley Additive Explanations) – global + local interpretability  
  - LIME (Local Interpretable Model-agnostic Explanations) – case-specific explanations  
- Achieved **97% accuracy** with Logistic Regression and Random Forest.  

---

## Objectives  

1. Predict **specific mental health disorders** (e.g., anxiety, depression, bipolar disorder).  
2. Incorporate **Explainable AI** for transparency in clinical settings.  
3. Provide a **prediction pipeline** for manual user input.  
4. Demonstrate potential for **real-world deployment** (e.g., hospital systems, mobile apps).  

---

## Tech Stack  

- **Language:** Python 3.x  
- **Environment:** Jupyter Notebook  
- **Libraries:**  
  - Data Processing: Pandas, NumPy  
  - ML Models: Scikit-learn  
  - Visualization: Matplotlib, Seaborn  
  - Explainability: SHAP, LIME  

---

## Installation & Setup  

1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/mental-health-disorder-prediction.git
   cd mental-health-disorder-prediction

2. Install dependencies:
	```bash
	pip install -r requirements.txt

3. Open the notebook:
	```bash
	jupyter notebook notebooks/MHDPrediction.ipynb

---

## Future Enhancements

- Explore deep learning models (LSTM, Transformers).
- Integration with Android app for real-time usage.
- Personalized risk assessment & monitoring.
- Integration with wearable devices.

---

## License

This project is for academic purposes as part of the Data Mining Lab, MIT Manipal (Apr 2025).
Licensed under the [MIT License](LICENSE)

---