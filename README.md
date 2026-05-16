# Part 2 - Computer Vision Problem Formulation and CNN Prototype

## Objective
The objective of this project is to build a Convolutional Neural Network (CNN) model for an image classification problem using an image dataset containing product defects such as dents and scratches.

---

## Problem Type
This dataset represents an Image Classification problem because the images are organized into separate folders representing different defect categories. The CNN model learns to classify images into their corresponding classes.

---

## Tasks Performed

### 1. Dataset Exploration
- Analyzed dataset structure
- Identified image classes
- Counted images per class
- Visualized sample images
- Checked image dimensions

### 2. Image Preprocessing
- Resized images to 128x128 pixels
- Normalized pixel values
- Split dataset into training and validation sets
- Applied data augmentation techniques

### 3. CNN Model Creation
The CNN model includes:
- Convolution layers
- ReLU activation functions
- MaxPooling layers
- Flatten layer
- Dense layers
- Softmax output layer

### 4. Model Training and Evaluation
- Trained CNN model on image dataset
- Evaluated training and validation accuracy
- Generated confusion matrix
- Generated classification report
- Displayed sample predictions

---

## CNN Concept Explanation

### What is Convolution?
Convolution is an operation used to extract important visual features such as edges, textures, and shapes from images.

### Why is Pooling Used?
Pooling reduces image dimensions and helps the network focus on important features while reducing computation.

### Why is ReLU Commonly Used?
ReLU introduces non-linearity and helps CNNs learn complex visual patterns efficiently.

### Why are CNNs Better for Images?
CNNs automatically learn spatial relationships and image features, making them more effective than regular feed-forward neural networks for image processing tasks.

---

## Business Use Case Mapping
This type of CNN-based computer vision system can be used in manufacturing industries for automated defect detection. The model can identify dents or scratches during product inspection, improving quality control and reducing manual effort.

---

## Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Repository Structure

```text
part-2-cnn-computer-vision/
│
├── README.md
├── notebook.ipynb
├── requirements.txt
├── sample_predictions/
│   └── prediction_outputs.png
└── results/
    ├── accuracy_loss_curves.png
    └── confusion_matrix.png
```

---

## Conclusion
The CNN model successfully learned visual features from the dataset and performed image classification effectively. The project demonstrates how convolutional neural networks can be applied to real-world computer vision tasks such as defect detection.
