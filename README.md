# 💵 Fake Money Detection using Deep Learning (Google Colab)

This project focuses on detecting **fake and real currency notes** using **Deep Learning (CNN)**. The model is trained on image datasets of currency notes and can classify whether a note is **genuine or counterfeit**.
The implementation is done using **Python, TensorFlow/Keras**, and executed in **Google Colab** for easy setup and GPU support.

---

## 🚀 Features

* Detects **Real vs Fake Currency Notes**
* Uses **Convolutional Neural Networks (CNN)**
* Easy to run on **Google Colab**
* Organized dataset structure (Train & Test)
* Pre-trained model folder included

---

## 🧠 Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* OpenCV
* Matplotlib
* Google Colab

---

## 📂 Project Structure

```
Fake_Money_Detection/
│
├── cnn.dense4_conv4/        # Saved CNN model files
├── train data/              # Training dataset
│   ├── Real/
│   └── Fake/
│
├── test data/               # Testing dataset
│   ├── Real/
│   └── Fake/
│
├── Real_Money_Detection.ipynb  # Main Colab notebook
└── README.md
```

---

## 📊 Dataset Description

* The dataset consists of **currency note images**
* Two classes:

  * **Real**
  * **Fake**
* Images are resized and normalized before training
* Dataset is divided into:

  * **Training Data**
  * **Testing Data**

> 📌 *Dataset is included in this repository for easy execution.*

---

## ⚙️ How to Run in Google Colab

### 1️⃣ Open Google Colab

Go to: [https://colab.research.google.com/](https://colab.research.google.com/)

### 2️⃣ Upload Notebook

Upload `Real_Money_Detection.ipynb`

### 3️⃣ Upload Dataset

* Upload the entire project folder **or**
* Mount Google Drive and place the dataset inside it

```python
from google.colab import drive
drive.mount('/content/drive')
```

### 4️⃣ Install Required Libraries

```python
pip install tensorflow opencv-python matplotlib numpy
```

### 5️⃣ Run All Cells

* Train the CNN model
* Evaluate accuracy
* Test predictions on sample images

---

## 📈 Model Details

* CNN with multiple **Convolution + Dense layers**
* Optimizer: **Adam**
* Loss Function: **Categorical Crossentropy**
* Achieves good accuracy for real-time detection scenarios

---

## ✅ Output

* Predicts whether the input currency image is:

  * **Real Money**
  * **Fake Money**
* Displays prediction confidence and accuracy graph

---

## 🔮 Future Enhancements

* Support for **multiple currency denominations**
* Real-time detection using **camera input**
* Mobile or Web App integration
* Improve accuracy using larger datasets

---

## 👨‍💻 Author

**Barani**
Engineering Student | AI & Computer Vision Enthusiast

