# 🫁 Pneumonia Detection using Transfer Learning (VGG16)

This project implements a deep learning model for pneumonia detection from chest X-ray images using Transfer Learning with the VGG16 architecture. The model was developed and trained in Google Colab using TensorFlow and Keras.

---

## 📌 Features

- Chest X-ray image classification
- Image preprocessing
- Data augmentation
- Transfer Learning using VGG16
- Model training and validation
- Performance evaluation
- Accuracy and loss visualization
- ROC Curve and Confusion Matrix

---

## 🛠️ Technologies Used

- Python
- Google Colab
- TensorFlow
- Keras
- VGG16
- NumPy
- Pandas
- Matplotlib
- Seaborn
- OpenCV
- Scikit-learn

---

## 📂 Project Structure

```
Pneumonia_Analysis/
│
├── PNEUMONIA_ANALYSIS.ipynb
├── requirements.txt
└── README.md
```

---

## 📊 Dataset

The project uses a chest X-ray image dataset consisting of two classes:

- Normal
- Pneumonia

The dataset is accessed using KaggleHub.

---

## 🔬 Model Pipeline

1. Load chest X-ray dataset
2. Perform image preprocessing
3. Apply data augmentation
4. Load pretrained VGG16 model
5. Fine-tune the classification layers
6. Train the model
7. Evaluate model performance
8. Generate predictions
9. Plot accuracy and loss curves
10. Visualize ROC Curve and Confusion Matrix

---

## 📈 Evaluation Metrics

- Training Accuracy
- Validation Accuracy
- Training Loss
- Validation Loss
- Confusion Matrix
- ROC Curve
- AUC Score

---

## ▶️ How to Run

1. Open the notebook in **Google Colab** or **Jupyter Notebook**.
2. Install the required libraries:

```bash
pip install -r requirements.txt
```

3. Run all notebook cells sequentially.

---

## 🚀 Future Improvements

- ResNet50 implementation
- EfficientNet implementation
- Grad-CAM visualization
- Streamlit web application
- Model deployment

---

## 👩‍💻 Author

**Mehak Sharma**

Developed as part of the **C-DAC Training Program**.

---

## 📜 License

This project is intended for educational and learning purposes.