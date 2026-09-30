# Waste Classification Using Transfer Learning ♻️

An image classification project using **TensorFlow, Keras, and VGG16 Transfer Learning** to classify waste images into **organic** and **recyclable** categories.

## Project Overview

This project was completed as the final project for IBM's **Deep Learning with Keras and TensorFlow** course on Coursera.

The project applies transfer learning with the VGG16 convolutional neural network to a waste-classification problem. The notebook covers dataset preparation, feature extraction, model training, fine-tuning, evaluation, and predictions on test images.
Full results with source codes are on the notebook.

## Technologies

- Python
- TensorFlow 2.17
- Keras
- VGG16
- NumPy
- Matplotlib
- Pillow
- Convolutional Neural Networks (CNNs)
- Transfer Learning

## Project Workflow

1. Configure the TensorFlow environment
2. Load and prepare image datasets
3. Create training, validation, and test generators
4. Load the VGG16 pre-trained model
5. Build the classification model
6. Freeze the base model and perform feature extraction
7. Train the model
8. Fine-tune the model
9. Compare training and validation performance
10. Generate predictions on test images

## Results

The notebook includes:

- Training and validation accuracy plots
- Training and validation loss plots
- Feature-extraction results
- Fine-tuning results
- Predictions on test images

The exact results are preserved in the completed notebook.

## Repository Structure

```text
waste-classification-transfer-learning/
├── README.md
├── notebooks/
│   └── Waste_Classification_Transfer_Learning.ipynb
├── results/
├── requirements.txt
├── .gitignore
└── LICENSE
```

## Running the Project

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/waste-classification-transfer-learning.git
cd waste-classification-transfer-learning
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

Activate it on Windows:

```bash
.venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Open the notebook

```bash
jupyter notebook
```

Open:

```text
notebooks/Waste_Classification_Transfer_Learning.ipynb
```

> **Dataset note:** The repository does not include the course dataset. Dataset used was provided internally by the IBM Deep Learning Course.

## Course

**Deep Learning with Keras and TensorFlow — IBM / Coursera**

## Author

**Musa Calvin Maroka**

Computer Science | Software Engineering | Machine Learning | Artificial Intelligence

## License

This repository is released under the MIT License. See `LICENSE` for details.
