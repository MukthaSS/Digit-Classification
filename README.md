# 🧠 Digit Classification using Deep Learning

A project to classify handwritten digits from the MNIST dataset using **Artificial Neural Networks (ANN)** and **Convolutional Neural Networks (CNN)** built with **TensorFlow/Keras**.

---

## 📌 Project Overview

This repository focuses on classifying digits (0–9) from grayscale images in the **MNIST dataset** using:

- ✅ **ANN (Artificial Neural Network)**
- ✅ **CNN (Convolutional Neural Network)**

You’ll explore how deep learning can be applied to image classification with impressive accuracy!

---

## 🧱 Model Architectures

### 🔹 ANN (Fully Connected Network)
- Input layer: 784 neurons (28x28 image flattened)
- Hidden layers: Dense layers with ReLU activation
- Output layer: 10 neurons (softmax)

### 🔹 CNN (Convolutional Neural Network)
- Convolutional layers with ReLU + MaxPooling
- Fully connected dense layers
-
- Final softmax classification

---

```bash
pip install tensorflow numpy matplotlib
```
## 📊 Model Performance

| Model | Accuracy (approx) |
|-------|-------------------|
| ANN   | ~98%              |
| CNN   | ~99.7%            |

> _Note: Actual accuracy may vary based on training parameters and hardware._

---

## 📷 Sample Output

![Sample predictions](https://upload.wikimedia.org/wikipedia/commons/2/27/MnistExamples.png)

---

## 💡 Key Concepts

- TensorFlow/Keras for rapid deep learning development  
- Dropout and MaxPooling for better generalization  
- Activation functions: ReLU, Softmax  
- Optimizer: Adam  
- Loss: Categorical Crossentropy  

---

## 🧠 What is MNIST?

The **MNIST dataset** is a classic dataset of handwritten digits:

- 60,000 training images  
- 10,000 test images  
- Each image is 28×28 pixels in grayscale

✅ No need to download manually — the dataset is automatically loaded via Keras.

---

## 🛠 Future Improvements

- Add model saving/loading (`.h5`)  
- Include confusion matrix and classification report  
- Add UI to draw your own digit for prediction  
- Try advanced architectures like ResNet or MobileNet  

---

## 🙌 Acknowledgements

- [TensorFlow](https://www.tensorflow.org/)  
- [Keras](https://keras.io/)  
- MNIST Dataset by Yann LeCun  

---

## 📬 Contact

Feel free to reach out or contribute!

**Author**: Muktha S  
**GitHub**: [@MukthaSS](https://github.com/MukthaSS)

