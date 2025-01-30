# Rice Leaf Disease Detection

## Introduction
Rice plants are highly vulnerable to various bacterial, viral, and fungal diseases, which pose significant threats to global rice production. Early detection is essential for ensuring healthy plant growth, enhancing food security, and supporting farmers worldwide. This project aims to identify infections in rice leaves using a machine learning-based approach.

## Dataset Overview
- **Dataset**: Rice Leaf Disease Dataset
- **Categories**: 
  - Leaf Smut
  - Brown Spot
  - Bacterial Leaf Blight
- **Total Images**: 120 images (40 per category)
- **Data Split**:
  - Training: 80%
  - Validation: 10%
  - Test: 10%

## Project Workflow
1. **Library Imports**: Loading essential Python libraries for data preprocessing and model creation.
2. **Data Loading**: Dividing the dataset into training, validation, and testing subsets.
3. **Data Preparation**: 
   - Image augmentation and preprocessing (resizing, normalization).
   - Batching for memory efficiency.
4. **Model Development**:
   - Convolutional Neural Network (CNN) architecture.
   - Compiling and visualizing the model.
   - Training using the dataset.
5. **Model Evaluation**: 
   - Model evaluation using accuracy and loss metrics.
   - Validation Accuracy: **91.67%**
   - Overall Accuracy: **84.38%**
6. **Model Testing**: Testing the model on unseen images from the test set.
7. **Model Saving**: Exporting the trained model for future use.

## Results
- **Training and Validation Accuracy**: Visualized graphs.
- **Final Metrics**:
  - Loss: **0.53**
  - Accuracy: **91.66%**

## Tools and Technologies
- **Programming Language**: Python
- **Libraries**: TensorFlow/Keras, NumPy, Matplotlib, Seaborn
- **Techniques**: Image Augmentation, CNN Architecture

## How to Run
1. Clone the repository.
2. Install dependencies using `pip install -r requirements.txt`.
3. Run the Jupyter notebook to train and evaluate the model.
