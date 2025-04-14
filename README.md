# 🐾 CNN Image Classifier: Cat vs. Dog

This repository contains a complete image classification project using **Convolutional Neural Networks (CNNs)** with TensorFlow and Keras. The model is trained to distinguish between images of cats and dogs.

---

## 📂 Project Structure

- `CNN.ipynb`: Jupyter Notebook with end-to-end implementation.
- `wiki/How_CNN_Works.md`: Technical explanation of CNN architecture.
- Dataset: Not included in this repository. Instructions for uploading from Google Drive are included in the notebook.

---

## 🚀 Features

- CNN implementation using Keras Sequential API
- Preprocessing and reshaping of RGB images
- Normalization of pixel data
- Feature extraction via Conv2D and MaxPooling2D
- Fully connected dense layers with activation functions
- Training and evaluation with binary cross-entropy loss
- Prediction on unseen test data

---

## 🧠 Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Google Colab & Google Drive

---

## 🗃️ Dataset

The dataset consists of:
- **2000 training images** (cats and dogs)
- **400 testing images**

Images are resized to 100x100 and include RGB color channels.

---

## 📊 Results

- The model achieves high training accuracy (>90%) but may overfit.
- Test accuracy: ~66% (can be improved with tuning or regularization).
- Outputs predictions with a probability score (sigmoid function).

---

## 📎 Instructions to Run

1. Clone the repo or upload the notebook to Google Colab.
2. Upload the dataset to your Google Drive.
3. Mount your Google Drive in Colab.
4. Follow the step-by-step code blocks to:
   - Load and preprocess data
   - Define and train the CNN model
   - Evaluate and make predictions on test data

---

## 📚 Wiki

For a detailed explanation of how CNNs work, see:  
📖 [wiki/How_CNN_Works.md](https://github.com/DeenoBajithaCode/CNN/wiki)

---

## 📌 Notes

- Make sure to normalize your data (divide by 255.0) before training.
- This model is a good base for experimenting with deeper architectures or regularization techniques to improve performance.

---

## 📬 Contact

Feel free to open issues or contribute to improve the project!

