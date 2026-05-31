# 🪙 Coin Detection using OpenCV

A simple Computer Vision project that detects and visualizes coins from an image using **OpenCV**, **Python**, and **Matplotlib**.

---

## 📖 Overview

This project demonstrates basic image processing techniques such as:

- Reading images using OpenCV
- Displaying images using Matplotlib
- Detecting coins from an image
- Understanding image preprocessing concepts
- Handling common image loading errors

This assignment is useful for beginners learning:
- Computer Vision
- OpenCV
- Image Processing in Python

---

## 🛠️ Technologies Used

- Python
- OpenCV (`cv2`)
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 📂 Project Structure

```bash
Coin-Detection-Assignment/
│
├── Coin-Detection-Assignment.ipynb
├── images/
│   └── CoinsA.png
└── README.md
```

---

## ⚙️ Installation

Install the required libraries:

```bash
pip install opencv-python matplotlib numpy
```

---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/Coin-Detection-Assignment.git
```

2. Navigate to the project folder:

```bash
cd Coin-Detection-Assignment
```

3. Launch Jupyter Notebook:

```bash
jupyter notebook
```

4. Open:

```bash
Coin-Detection-Assignment.ipynb
```

5. Ensure the image exists at:

```bash
./images/CoinsA.png
```

6. Run all notebook cells.

---

## 📸 Sample Code

```python
import cv2
import matplotlib.pyplot as plt

# Image path
imagePath = "./images/CoinsA.png"

# Read image
image = cv2.imread(imagePath)

# Display image
plt.imshow(image[:,:,::-1])
plt.title("Original Image")
plt.show()
```

---

## 🔍 Features

✅ Coin image loading  
✅ Image visualization  
✅ Coin detection concepts  
✅ OpenCV image processing  
✅ Error handling for missing image paths  

---

## ⚠️ Common Errors

### 1. DATA_PATH not defined

#### Error
```python
NameError: name 'DATA_PATH' is not defined
```

#### Fix
```python
DATA_PATH = "./"
```

---

### 2. Image not loading

#### Error
```python
AttributeError: 'NoneType' object has no attribute 'copy'
```

#### Cause
Incorrect image path.

#### Fix
Ensure the image exists at:

```bash
./images/CoinsA.png
```

---

### 3. NoneType object is not subscriptable

#### Error
```python
TypeError: 'NoneType' object is not subscriptable
```

#### Cause
`cv2.imread()` failed to load the image.

#### Fix
Check the image path and filename carefully.

---

## 📈 Expected Output

- Original image displayed successfully
- Coins detected and visualized
- Proper image preprocessing workflow

---

## 🎯 Learning Outcomes

By completing this project, you will learn:

- Basics of OpenCV
- Image handling in Python
- Visualization using Matplotlib
- Debugging image path issues
- Introduction to Computer Vision concepts

---

## 🚀 Future Improvements

- Real-time coin detection using webcam
- Coin classification by size
- Currency recognition system
- Deep Learning based object detection

---

## 👨‍💻 Author

Created as part of a Computer Vision / Image Processing assignment using Python and OpenCV.

---

## 🌟 Star This Repository

If you found this project useful, give it a ⭐ on GitHub!
