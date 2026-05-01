# Brain Tumor Detection in MRI 🧠🤖

Deep Learning model to detect brain tumors in MRI images using Convolutional Neural Networks (CNN).

## Results
- 82% accuracy on test data
- Improved from 67% using Data Augmentation
- 87% precision detecting tumors

## Architecture
- 2 Convolutional layers with MaxPooling
- Dropout layers to prevent overfitting
- Data Augmentation to handle small dataset (253 images)

## Technologies
- Python 3.13
- TensorFlow 2.21, Keras
- OpenCV, NumPy, Matplotlib

## Conclusion
This project demonstrates the application of Deep Learning for medical image analysis,  specifically brain tumor detection in MRI scans — one of the most critical tasks in modern neuroradiology.

Starting with a baseline CNN that achieved 67% accuracy, the model struggled due to the limited dataset size (253 images). By applying Data Augmentation techniques (rotation, flipping, zoom, shifting), the model improved to 82% accuracy with 87% 
precision in tumor detection.

Key findings:
- Data Augmentation is essential when working with small medical datasets
- Overfitting is a common challenge in medical imaging AI due to data scarcity
- Even with limited data, CNNs can learn meaningful patterns from MRI scans

In a real clinical setting, this model would be trained on thousands of images and combined with radiologist expertise — not as a replacement, but as a decision support tool that flags suspicious scans for priority review. This type of AI-assisted radiology is already being deployed by companies like Siemens Healthineers and Philips Medical, representing one of the fastest-growing areas in MedTech.

## Data Source
Brain MRI Images for Brain Tumor Detection - Kaggle
