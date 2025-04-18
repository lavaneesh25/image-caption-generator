# image-caption-generator
# 🖼️ Image Caption Generator using CNN-LSTM

## 📌 Overview
This project implements an Image Captioning system that generates natural language descriptions for images. It combines **Convolutional Neural Networks (CNNs)** to extract image features and **Long Short-Term Memory (LSTM)** networks to generate grammatically correct captions.

---

## 🧠 Model Architecture

- **CNN Encoder**: Uses a pre-trained model (e.g., VGG16, InceptionV3, or ResNet) to extract feature vectors from input images.
- **LSTM Decoder**: Takes the extracted features and generates captions word by word.
- **Tokenizer**: Used to convert text into sequences for training and inference.

---

## 📂 Dataset

- **Dataset Used**: [Flickr8k/Flickr30k/MSCOCO]
- Includes images and multiple human-generated captions per image.
- Preprocessing includes resizing, tokenizing, and padding sequences.

> Note: Dataset should be downloaded separately due to size constraints.

---

## 🛠️ Requirements

- Python 3.x  
- TensorFlow / Keras  
- NumPy, Matplotlib, PIL  
- Jupyter Notebook  
- NLTK (for text preprocessing)  
- tqdm (for training progress bars)

Install dependencies:
```bash
pip install tensorflow keras numpy matplotlib nltk tqdm pillow
