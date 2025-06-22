# 🧠 Image Classification on CIFAR-10 using Random Forest and CNN

This project performs image classification on the CIFAR-10 dataset using two different models: a classical **Random Forest** classifier and a deep learning-based **Convolutional Neural Network (CNN)**. The goal is to compare their performance and highlight the effectiveness of CNNs in handling image data.

---

## 📚 Dataset  
The **CIFAR-10** dataset contains 60,000 32x32 color images across 10 categories such as airplane, automobile, bird, cat, etc.

---

## ⚙️ Methods  
- **Random Forest**: A traditional machine learning model using pixel values as features.  
- **CNN**: A deep learning model designed to learn hierarchical spatial features from images.

---

## 📊 Results Overview  
CNN significantly outperformed Random Forest in classification accuracy:  
- **CNN Accuracy**: 0.7030  
- **Random Forest Accuracy**: 0.3884  

CNN achieved much higher precision, recall, and F1-score in most categories due to its ability to capture spatial and contextual information in images, which Random Forest lacks.

---

## 🔍 Key Insight  
The CNN model not only achieved better overall accuracy but also demonstrated more balanced performance across all classes. This shows how deep learning architectures are far more suitable for complex image classification tasks compared to traditional machine learning algorithms.

---

## 🚀 Future Scope  
- Experiment with deeper CNN architectures (e.g., ResNet, VGG).  
- Apply data augmentation for better generalization.  
- Explore ensemble or hybrid models.

---

This project serves as a practical demonstration of the power of CNNs over conventional models in computer vision tasks.



```python

```
