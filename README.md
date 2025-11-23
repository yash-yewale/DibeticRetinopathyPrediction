# AI-Assisted Diabetic Retinopathy Detection 👁️

This project uses Deep Learning (EfficientNetB0) to detect the severity of Diabetic Retinopathy from retinal fundus images. It classifies images into 5 stages of severity to assist in early diagnosis.

### 📊 Results
* **Quadratic Weighted Kappa (QWK):** 0.86 (High alignment with clinical grading)
* **Accuracy:** 84%

![Results](path/to/your_classification_report_screenshot.png)
*(Replace with your Classification Report image)*

### 🛠️ How it Works
1.  **Preprocessing:** Uses Ben Graham's method (Gaussian Blur) to normalize lighting in retinal scans.
2.  **Training:** Fine-tuned EfficientNetB0 with **Class Weights** to handle the heavy data imbalance.
3.  **Deployment:** Includes a Gradio web interface for easy testing.

### 📱 Demo
![App Interface](path/to/your_app_screenshot.png)
*(Replace with your App Interface image)*

### 📂 Files
* `Diabetic_Retinopathy.ipynb`: The complete training and evaluation notebook.
* `app.py`: The Gradio application script.
* `requirements.txt`: List of libraries used.

---
*Created as a Deep Learning project using TensorFlow and Keras.*
