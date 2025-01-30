**Rice Leaf Disease Detection**
Introduction
Rice plants are highly vulnerable to various bacterial, viral, and fungal diseases, which pose significant threats to global rice production. Early detection is essential for ensuring healthy plant growth, enhancing food security, and supporting farmers worldwide. This project aims to identify infections in rice leaves using a machine learning-based approach.

Dataset Overview
The dataset comprises 120 images of rice leaves, categorized into three disease types:

Leaf Smut
Brown Spot
Bacterial Leaf Blight
Each category contains 40 images, and the dataset is split into training, validation, and testing subsets for model development and evaluation.

Project Workflow
The project follows these key steps:

Library Imports: Loading necessary Python libraries for data preprocessing and model creation.
Data Loading: Splitting the dataset into training, validation, and testing subsets using the split-folders library.
Data Preparation:
Creating batches for efficient memory usage.
Preprocessing images through resizing, normalization, and augmentation.
Model Development:
Building a CNN with convolutional, pooling, and fully connected layers.
Compiling the model and visualizing its architecture.
Training the model with the preprocessed dataset.
Model Evaluation:
Evaluating performance using accuracy and loss metrics.
Validation Accuracy: 91.67%
Overall Accuracy: 84.38%
Model Testing: Testing the model on multiple images from the test dataset.
Model Saving: Exporting the trained model for future use.
Results
Training and Validation Accuracy: Displayed graphically for performance comparison.
Training and Validation Loss: Analyzed for insights into model optimization.
Final Metrics:
Loss: 0.53
Accuracy: 91.66%
Tools and Technologies
Programming Language: Python
Libraries: TensorFlow/Keras, NumPy, Matplotlib, Seaborn
Techniques: Image Augmentation, CNN Architecture
