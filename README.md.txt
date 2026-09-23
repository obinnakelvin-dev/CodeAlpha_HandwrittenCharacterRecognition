 CodeAlpha Handwritten Character Recognition

A handwritten character recognition system built using a Convolutional Neural Network (CNN) and the EMNIST Balanced dataset.

 Project Overview

This project uses deep learning to recognize handwritten digits and letters.

The model was trained on the EMNIST Balanced dataset containing 47 different character classes.

 Dataset

- Dataset: EMNIST Balanced
- Training images: 112,800
- Testing images: 18,800
- Image size: 28 × 28 pixels
- Number of classes: 47

 Model

The project uses a Convolutional Neural Network (CNN) built with TensorFlow and Keras.

 Architecture

- Conv2D: 32 filters
- MaxPooling2D
- Conv2D: 64 filters
- MaxPooling2D
- Conv2D: 128 filters
- Flatten
- Dense: 128 neurons
- Dropout
- Output layer: 47 classes

 Results

The trained model achieved:

- Test Accuracy: **88.47%**
- Macro Precision: **88.65%**
- Macro Recall: **88.47%**
- Macro F1-Score: **88.37%**

The model was evaluated on 18,800 unseen test images.

 Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab
- EMNIST Balanced

 Project Files

text
CodeAlpha_HandwrittenCharacterRecognition/
│
├── handwritten_character_recognition.ipynb
├── handwritten_character_recognition.keras
├── character_mapping.json
└── README.md