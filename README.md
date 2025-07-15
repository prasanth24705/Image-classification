# Image-classification

# Cats vs Dogs Image Classifier

A simple Convolutional Neural Network (CNN) built with TensorFlow and Keras to classify images of cats and dogs.

This project uses a real-world dataset, performs data augmentation, builds a custom CNN, and tests predictions on new images. Perfect for practicing image classification and adding to your data science portfolio!

# Dataset

- Dataset: [Cats vs Dogs filtered dataset](https://storage.googleapis.com/mledu-datasets/cats_and_dogs_filtered.zip)
- Source: Microsoft
- Structure:
  - `train/` — images for training (`cats` and `dogs` folders)
  - `validation/` — images for validation (`cats` and `dogs` folders)

---

# How to Run

1. Open the notebook:
   Use `cats_vs_dogs.ipynb` in [Google Colab](https://colab.research.google.com/) for easy execution with GPU.

2. Steps covered:* 
    Download and extract dataset  
    Create data generators with augmentation  
    Build a custom CNN  
    Train the model and plot accuracy/loss  
    Save the trained model (`.keras` format)  
    Upload new images and test predictions

3. Run test predictions:
   Upload a new cat or dog image in Colab, preprocess it, and let the model classify it with confidence.


# Results
Model: Simple CNN with 3 convolutional blocks and dense layers.
Accuracy: Achieved ~85% validation accuracy in under 10 epochs.
Improvements: You can boost performance further using transfer learning (e.g., MobileNet, ResNet).




# Requirements

- Python >= 3.8
- TensorFlow >= 2.x
- Keras >= 3.x
- Google Colab (recommended for free GPU)




# References

- [TensorFlow Official Tutorials](https://www.tensorflow.org/tutorials/images/classification)
- [Keras Documentation](https://keras.io/)

