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


