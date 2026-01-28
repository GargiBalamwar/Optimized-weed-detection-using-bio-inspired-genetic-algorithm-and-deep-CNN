# Optimized-weed-detection-using-bio-inspired-genetic-algorithm-and-deep-CNN
Weed Detection using GA-Optimized CNN

A deep learning-based **weed detection system** that uses a **Genetic Algorithm (GA)-optimized Convolutional Neural Network (CNN)** to classify weed species from agricultural field images with high accuracy and faster convergence.
Developed to support **precision agriculture** and reduce manual weed monitoring efforts.

Features

* GA-based optimization of CNN hyperparameters
* High-accuracy weed species classification
* Reduced training time and faster model convergence
* Trained on the **DeepWeeds dataset** (8 weed species + background)
* Built with **TensorFlow** and **Keras**

Model Overview

| **Metric**        | **Base CNN** | **GA-Optimized CNN** |
| ----------------- | ------------ | -------------------- |
| **Accuracy**      | 91.5%        | **96.8%**            |
| **Precision**     | 90.2%        | **96.5%**            |
| **Recall**        | 89.8%        | **97.1%**            |
| **F1-Score**      | 90.0%        | **96.8%**            |
| **Training Time** | High         | **Reduced**          |

The GA-optimized CNN demonstrates **improved performance** and **faster convergence** compared to the baseline CNN.

Technologies Used

* **Python 3**
* **TensorFlow / Keras**
* **NumPy, Matplotlib, OpenCV**
* **Genetic Algorithm for hyperparameter tuning**


Dataset

* **DeepWeeds Dataset**
* 17,509 labeled images (8 weed species + 1 background class)
* Images resized to **256×256×3** for training



License

This project is released under the **MIT License**.
Feel free to use, modify, and share with credit.
