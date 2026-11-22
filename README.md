# 🔍 AI vs Real Image Detection using CNN

Can you tell whether an image is AI-generated or real? This project uses a Convolutional Neural Network (CNN) to classify images into two categories: **AI-Generated** and **Real**.

## 🎯 Project Overview

This project was developed as part of a CNN workshop under the guidance of seniors at Insight AI Club , MIT-WPU. It explores how deep learning and computer vision can be used to distinguish AI-generated images from real-world images.

## 🧠 Model Architecture

- Convolutional Neural Network (CNN)
- 3 Convolutional layers
- 3 Max Pooling layers
- Fully Connected Dense layer (256 neurons)
- Sigmoid output layer for binary classification

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Pandas
- Scikit-learn
- Jupyter Notebook

## 📊 Results

Training and validation performance visualizations, along with sample predictions, are available in the [`results/`](results/) folder.

- Accuracy graph
- Loss graph
- Sample predictions

## 📁 Repository Structure

```text
├── CNN.ipynb
├── results/
│   ├── accuracy.png
│   ├── loss.png
│   ├── predictions.png
│   └── README.md
├── requirements.txt
└── README.md
```

## 🚀 Getting Started

1. Clone this repository:

   ```bash
   git clone https://github.com/codernarayanidesh2907/AI-Unmasked-.git
   ```

2. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Open the notebook:

   ```bash
   jupyter notebook CNN.ipynb
   ```

4. Place the dataset in the appropriate local directory before running the notebook.

**Note:** The original dataset is not included in this repository.

👥 Author : Narayani Deshpande 

