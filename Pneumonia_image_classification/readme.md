# PneumoniaMNIST Image Classification

This project implements a binary image classification model to detect pneumonia from chest X-ray images using the **PneumoniaMNIST** dataset from the **MedMNIST** collection. The goal is to classify images as either **"normal" (0)** or **"pneumonia" (1)** using a Convolutional Neural Network (CNN) built with **PyTorch**.

---

## Dataset

The PneumoniaMNIST dataset is automatically downloaded when running the notebook. Below are the key details:

- **Classes**:  
  - 0: Normal  
  - 1: Pneumonia

- **Channels**: 1 (grayscale)  
- **Image Size**: 28x28 pixels

### Dataset Splits

- **Training**: 4,708 images  
- **Validation**: 524 images  
- **Test**: 624 images

---

## CNN Architecture Overview

Convolutional Neural Networks (CNNs) excel at capturing spatial features (such as edges, shapes, and textures) in images. They work by stacking different types of layers:

1. **Convolutional Layers** – Detect local patterns in small regions of the image  
2. **Pooling Layers** – Downsample the spatial dimensions, helping the model focus on the most important features  
3. **Fully Connected Layers** – Combine all learned features to produce the final classification output

---

## Future Improvements

- Implement data augmentation to improve generalization  
- Experiment with deeper CNN architectures (e.g., ResNet variants)  
- Add early stopping and learning rate scheduling  
- Evaluate performance with metrics like AUC and F1-score  
- Integrate model explainability tools (e.g., Grad-CAM)  

---

## License

This project is for educational and research purposes.
 