# **CNN Image Classification**  

This repository provides a step-by-step guide for building a **Convolutional Neural Network (CNN)** to classify images. The project is organized into **four notebooks** that take you through the complete workflow, from understanding CNNs to training a model.

---

## **Repository Structure**  

The project is broken into **four main notebooks**:  

```
Notebooks
├── 01_intro.ipynb             # Introduction to CNNs and basic concepts
├── 02_how_it_work.ipynb       # Explanation of how CNNs work with examples
├── 03_folders_genrator.ipynb  # Organizing data and using ImageDataGenerator
└── 04_train_model.ipynb       # Building, training, and evaluating the CNN model
```

1. **01_intro.ipynb**  
   - Introduction to Convolutional Neural Networks (CNNs).  
   - Discusses what CNNs are and their use cases.  

2. **02_how_it_work.ipynb**  
   - Step-by-step explanation of CNN components:  
     - Convolutional Layers  
     - Pooling Layers  
     - Fully Connected Layers  

3. **03_folders_genrator.ipynb**  
   - Demonstrates how to:  
     - Organize image data into folders.  
     - Use **ImageDataGenerator** for data loading and augmentation.  

4. **04_train_model.ipynb**  
   - Builds and trains the CNN model.  
   - Implements techniques to reduce overfitting:  
     - Regularization  
     - Dropout  
     - Early Stopping  
   - Visualizes results.  

---

## **Technologies Used**  

- **Python**  
- **TensorFlow/Keras**  
- **NumPy**  
- **Matplotlib**  
- **Jupyter Notebook**  

---

## **How to Run the Project**  

1. **Clone the Repository**:  
   ```bash
   git clone https://github.com/ManaSaleh/cnn-image-classification.git
   cd cnn-image-classification
   ```

2. **Install Required Libraries**:  
   Install the dependencies using `pip`:  
   ```bash
   pip install tensorflow matplotlib numpy
   ```

---

## **Observations**  

- Adding **L2 regularization** and **Dropout** helped reduce overfitting.  
- **Early Stopping** improved generalization by stopping training at the optimal point.  
- Data augmentation improved performance by generating diverse training examples.

---
