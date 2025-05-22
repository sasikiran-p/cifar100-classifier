
# CIFAR100 Image Classification Project

A deep learning project for fine-grained image classification using the CIFAR-100 dataset.

## 📊 Overview

This project focuses on building a Convolutional Neural Network (CNN) to classify images from the CIFAR-100 dataset. The dataset contains 60,000 32x32 color images divided into 100 fine-grained categories.

## 🔧 Features

- Custom CIFAR-100 data loader using Keras and NumPy
- Image reshaping, normalization, and label encoding
- Support for both 'fine' and 'coarse' labels
- Compatibility with both 'channels_first' and 'channels_last'
- Handles multi-class classification and fine-grained categories
- Ready-to-train input for CNNs

## 🛠 Technologies Used

- Python
- Keras
- NumPy
- TensorFlow (optional for model training)

## 🚀 How to Use

1. Clone the repository:

```bash
git clone https://github.com/yourusername/cifar100-classifier.git
cd cifar100-classifier
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Load and preprocess the CIFAR-100 dataset:

```python
from cifar100 import load_data
(x_train, y_train), (x_test, y_test) = load_data(label_mode="fine")
```

4. Train your CNN model using your preferred architecture.

5. Evaluate model performance and visualize results.

## 📁 Project Structure

```
cifar100-classifier/
├── cifar100.py            # Custom CIFAR-100 loader script
├── train_model.py         # CNN training script (optional)
├── README.md              # Project documentation
├── requirements.txt       # Python dependencies
```

## 🧠 About CIFAR-100

The CIFAR-100 dataset is a well-known computer vision dataset used for evaluating fine-grained image classification models. For more info, visit [CIFAR-100](https://www.cs.toronto.edu/~kriz/cifar.html).

## 📬 Contact

For questions or suggestions, reach out to [sasikiran422@gmail.com](mailto:sasikiran422@gmail.com).
