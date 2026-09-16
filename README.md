# Breast Cancer Classification using PyTorch

An end-to-end Deep Learning binary classification pipeline built with **PyTorch** and **Scikit-Learn** to predict breast cancer malignancy based on clinical features.

## 📌 Features
- Data standardization using `StandardScaler`.
- Custom Multi-Layer Perceptron (MLP) architecture built with `nn.Module`.
- Binary Cross Entropy Loss (`BCEWithLogitsLoss`) and `Adam` optimizer.
- Comprehensive model evaluation with **Accuracy**, **Precision**, **Recall**, and **Confusion Matrix**.

## 🛠️ Tech Stack
- **Framework:** PyTorch
- **Data Processing & Metrics:** Scikit-Learn, Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn

## 🚀 How to Run

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/MoBa-create/pytorch-breast-cancer-classification.git](https://github.com/YOUR_USERNAME/pytorch-breast-cancer-classification.git)
   cd pytorch-breast-cancer-classification

1 . Install dependencies:

	pip install -r requirements.txt

2 . Run the script:

	python main.py

📊 Results

Test Accuracy: ~96.5%

Includes automated confusion matrix generation saved as confusion_matrix.png.