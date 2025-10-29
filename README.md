# Plant Disease Detection using Machine Learning

## 📘 Project Overview

This project focuses on detecting plant diseases from leaf images using machine learning techniques. The goal is to classify whether a plant is healthy or affected by a particular disease based on visual symptoms. The model leverages image-based learning to assist farmers and agricultural researchers in early disease detection and preventive care.

## 🧠 Objective

To build a machine learning model that can:

* Accurately identify diseases from plant leaf images.
* Automate the monitoring process and reduce manual inspection time.
* Demonstrate the potential of AI in precision agriculture.

## 🗂️ Dataset Description

The dataset used is the **PlantVillage dataset**, which contains thousands of labeled images of healthy and diseased plant leaves.
Each image is categorized based on:

* **Plant type** (e.g., tomato, potato, maize, etc.)
* **Disease label** (e.g., early blight, late blight, leaf spot, etc.)

Data preprocessing steps include:

* Image resizing and normalization.
* Splitting into training, validation, and testing sets.
* Optional augmentation to balance the dataset and improve generalization.

## 🧩 Model Architecture

The notebook implements a **Convolutional Neural Network (CNN)** built using TensorFlow/Keras.
Model structure typically includes:

1. Convolutional layers for feature extraction.
2. Max-Pooling layers for dimensionality reduction.
3. Flatten and Dense layers for classification.
4. Softmax activation for multi-class output.

The model learns discriminative patterns of disease from pixel data during training.

## ⚙️ Training Process

1. **Data Loading & Preprocessing:** Images are loaded, resized, and normalized.
2. **Model Compilation:** The model is compiled using `categorical_crossentropy` loss and `adam` optimizer.
3. **Training:** Model is trained with early stopping and validation checks to prevent overfitting.
4. **Evaluation:** Accuracy, Precision, Recall, and F1-Score are calculated on the test dataset.

## 📈 Results & Evaluation

The model achieves strong performance on validation data, with metrics such as:

* **Accuracy:** ~95% (approx., depends on training setup)
* **Precision / Recall / F1-Score:** Used for deeper performance evaluation.
* **Confusion Matrix:** Visualizes prediction correctness across all classes.

Model predictions can also be visualized for a subset of test images to verify results qualitatively.

## 🧰 Dependencies

Install the required libraries before running the notebook:

```bash
pip install tensorflow keras numpy matplotlib scikit-learn opencv-python
```

## 🚀 How to Run

1. Clone the repository or download the notebook:

   ```bash
   git clone https://github.com/<your-username>/Plant-Disease-Detection.git
   ```
2. Open the Jupyter Notebook:

   ```bash
   jupyter notebook "Plant Disease Detection Code.ipynb"
   ```
3. Run all cells sequentially.
4. Upload or point to the dataset path when prompted.

## 🪄 Future Improvements

* Integrate transfer learning (e.g., MobileNetV2, EfficientNet).
* Deploy as a web app using Flask or Streamlit.
* Expand to multi-crop disease classification.
* Add real-time detection via camera feed.

## 👨‍💻 Author

**Mayank Mehta**
Computer Engineering Student, Fr. Conceicao Rodrigues College of Engineering
*Focused on applying AI and ML to solve real-world problems.*

---

Would you like me to tailor this README for **academic submission** (more formal and report-style) or keep it in this **GitHub-friendly developer tone**?
