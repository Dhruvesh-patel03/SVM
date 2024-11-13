# SVM

# Cats vs Dogs Classification with SVM

This project uses a **Support Vector Machine (SVM)** model to classify images of cats and dogs. It preprocesses grayscale images, resizes them, and trains a linear SVM to accurately distinguish between the two categories.

---

## 📁 Directory Structure

- **`test`**: Directory containing subfolders for each category:
  - `test/cats/`: Images of cats.
  - `test/dogs/`: Images of dogs.
- **`code.py`**: Script to preprocess the dataset, train the SVM model, and evaluate its performance.

---

## 📊 Features

- **Grayscale Conversion**: All images are converted to grayscale for simplicity and uniformity.
- **Resizing**: Images are resized to 64x64 pixels for feature consistency.
- **Flattening**: Each image is flattened into a 1D vector to serve as input features.
- **Train-Test Split**: Data is split into 80% training and 20% testing sets.
- **Linear Kernel SVM**: A linear SVM is used for binary classification.
- **Performance Metrics**: The model outputs accuracy, a confusion matrix, and a detailed classification report.

---

## 🚀 How to Run

### 1. Setup Environment
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/cats-vs-dogs-svm.git
   cd cats-vs-dogs-svm
   ```
2. Install required libraries:
   ```bash
   pip install numpy opencv-python matplotlib scikit-learn seaborn
   ```

### 2. Add Dataset
Place your dataset in the `test` directory as follows:
- `test/cats/`: Images of cats.
- `test/dogs/`: Images of dogs.

### 3. Run the Script
Execute the Python script:

## 📈 Outputs

1. **Accuracy**: The percentage of correctly classified images.
2. **Confusion Matrix**: A heatmap visualization showing true vs. predicted labels.
3. **Classification Report**: Metrics such as precision, recall, and F1-score for both categories.
