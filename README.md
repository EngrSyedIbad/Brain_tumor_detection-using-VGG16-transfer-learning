# 🧠 Brain Tumor Detection Using Transfer Learning (VGG16)

This project implements a brain tumor classification system using **VGG16** and **transfer learning**. The goal is to detect tumors from brain MRI scans, enabling early and accurate diagnosis with minimal training data.

---

## ✅ Sample Results

| Input MRI | Predicted Label | Ground Truth |
|-----------|-----------------|---------------|
| ![sample1](images/sample1.jpg) | Tumor         | Tumor        |
| ![sample2](images/sample2.jpg) | No Tumor      | No Tumor     |

> Replace `images/sample1.jpg` and `images/sample2.jpg` with actual image paths.

---

## 📈 Performance Summary

- **Model**: VGG16 (fine-tuned top layers)
- **Training Accuracy**: ~98%
- **Validation Accuracy**: ~96%
- **Loss Curve**: Smooth convergence
- **Confusion Matrix**: High sensitivity and specificity

---

## 📁 Project Structure

- `Brain_tumor_detection_using_(VGG16)_transfer_learning.ipynb`: Main notebook
- `images/`: Directory for sample results (optional)
- `models/`: (Optional) Saved trained models

---

## 📦 Dataset

You can download the dataset used for training from:

🔗 [Kaggle Brain MRI Dataset (Tumor/No Tumor)](https://www.kaggle.com/navoneel/brain-mri-images-for-brain-tumor-detection)

> Make sure to upload the dataset to your Google Drive when using Google Colab.

---

## 🛠 Requirements

- Python 3.x  
- TensorFlow / Keras  
- NumPy, Pandas, Matplotlib  
- Google Colab (recommended for GPU support)

---

## 🚀 How to Run

1. Open the notebook in [Google Colab](https://colab.research.google.com/).
2. Mount Google Drive to access your dataset:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
   ```
3. Modify dataset paths if needed.
4. Run all cells sequentially.
5. Evaluate the results and fine-tune the model as desired.

---

## 📜 License

This project is available under the [MIT License](https://opensource.org/licenses/MIT).
