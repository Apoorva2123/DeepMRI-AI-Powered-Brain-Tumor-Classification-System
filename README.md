# DeepMRI: AI-Powered Brain Tumor Classification System

DeepMRI is an AI-driven project focused on classifying brain tumors from MRI scans using deep learning techniques. The goal of this project is to build an accurate and reliable model that can assist in early detection and diagnosis, helping medical professionals make faster and more informed decisions. The system is designed with simplicity, performance, and real-world healthcare impact in mind.

## Dataset

The dataset used for this project is publicly available on Kaggle:  
[Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)

### Why this dataset?
- It contains real MRI brain scan images categorized into different tumor classes.
- The dataset is well-structured and commonly used for medical imaging research.
- It provides enough samples to train and evaluate deep learning models effectively.
- Using a public dataset ensures transparency and reproducibility of results.

## Goal of the Project

The primary goal of this project is to:
- Accurately classify brain MRI images into tumor and non-tumor categories (or multiple tumor classes).
- Compare different deep learning models and identify the best-performing approach.
- Gain hands-on experience with medical image preprocessing, model training, and evaluation.

## Project Workflow
This project follows a structured yet challenging pipeline, addressing real-world complexities involved in medical image analysis:

1. **Understanding the Problem Domain**
   - Brain tumor detection is a high-stakes medical task where accuracy and reliability are critical.
   - Even small classification errors can have serious real-world implications, making model design and evaluation challenging.
     
2. **Data Loading**
   - MRI images are loaded from the dataset and organized by class labels.
  
3. **Data Exploration & Challenges**
   - MRI images vary in size, quality, and contrast.
   - Tumor features can be subtle and difficult to distinguish, even for deep learning models.
   - Class imbalance and visual similarity between tumor types add to the complexity.
  
4. **Data Preprocessing**
   - Images are resized and normalized to ensure consistency.
   - Noise reduction and data preparation are carefully handled to preserve medical details.
   - The dataset is split into training and testing sets to ensure fair evaluation.

5. **Model Architecture Design**
   - Multiple deep learning architectures are explored to understand how different network designs impact performance on medical images.
   - Convolutional Neural Networks (CNNs) are carefully structured to capture both low-level features (edges, textures) and high-level features (tumor shapes and regions).
   - Increasing model depth can improve feature learning, but it also increases the risk of overfitting, especially with limited medical data.
   - To address this, layers such as convolution, pooling, and dropout are strategically combined to balance accuracy and generalization.
   - Hyperparameters including learning rate, number of layers, batch size, and number of filters are tuned to ensure the model learns meaningful patterns without memorizing the training data.
   - The final architecture is chosen based on stable training behavior and strong performance on unseen MRI scans.
  
6. **Model Training**
   - Models are trained on high-dimensional image data, requiring careful monitoring of loss and accuracy.
   - Training deep networks on medical data is computationally intensive and time-sensitive.

7. **Evaluation & Overfitting Analysis**
   - Training and testing performance are compared to detect overfitting.
   - Special attention is given to generalization, as medical models must perform well on unseen data.

8. **Model Selection & Optimization**
   - The best-performing model is selected based on accuracy, stability, and consistency.
   - Performance trade-offs are analyzed to ensure reliability rather than just high accuracy.

9. **Final Validation**
   - The final model is validated on unseen MRI scans to simulate real-world deployment.
   - Results demonstrate the potential of deep learning in supporting medical diagnosis.

## What Was Accomplished

- Successfully built and trained multiple deep learning models for brain tumor classification.
- Achieved strong accuracy on the test dataset.
- Identified the most effective model for this task.
- Gained insights into handling medical image data and model evaluation.

## Best Performing Model

The **best-performing model** achieved the highest test accuracy while maintaining a good balance between training and testing performance, indicating minimal overfitting.

- **Model Type:** Deep Learning CNN (RBF / CNN-based architecture)
- **Performance:** High classification accuracy on unseen MRI scans
- **Key Strength:** Strong generalization and reliable predictions





