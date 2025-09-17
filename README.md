# 🖼️ Image Processing Lab

## Introduction
This project is a Jupyter Notebook that demonstrates various **image processing techniques** using **OpenCV** and **NumPy**, along with deep learning experiments using **TensorFlow/Keras**.  

It covers fundamental transformations, enhancements, and convolutional neural network (CNN) training on the MNIST dataset.

---

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Techniques Implemented](#techniques-implemented)
- [Dependencies](#dependencies)
- [Examples](#examples)
- [License](#license)

---

## Features
- ✅ Image negative transformations (color, grayscale, binary).  
- ✅ Logarithmic & gamma transformations for intensity adjustment.  
- ✅ Arithmetic operations: addition, subtraction, multiplication, division.  
- ✅ Brightness and contrast control.  
- ✅ Contrast stretching.  
- ✅ Histogram equalization.  
- ✅ Convolutional Neural Networks (CNN) for MNIST digit recognition.  
- ✅ Training progress monitoring with `tqdm`.  

---

## Installation
Clone the repository and install dependencies:

```bash
git clone https://github.com/yourusername/ImageProcessingLab.git
cd ImageProcessingLab
pip install -r requirements.txt
```

If `requirements.txt` is missing, install manually:

```bash
pip install opencv-python numpy matplotlib tensorflow tqdm
```

---

## Usage
Run the Jupyter Notebook:

```bash
jupyter notebook ImageProcessingLab.ipynb
```

---

## Techniques Implemented
1. **Image Negatives**  
   - Color image negative  
   - Grayscale negative  
   - Binary negative  

2. **Transformations**  
   - Logarithmic transformation  
   - Gamma correction  

3. **Image Arithmetic**  
   - Weighted addition  
   - Subtraction  
   - Multiplication  
   - Division  

4. **Enhancements**  
   - Brightness & contrast adjustment  
   - Contrast stretching  
   - Histogram equalization  

5. **Deep Learning**  
   - CNN for MNIST classification (using TensorFlow/Keras)  
   - Accuracy tracking with training/validation plots  
   - Custom `tqdm` progress bar callback  

---

## Dependencies
- Python 3.8+  
- OpenCV (`opencv-python`)  
- NumPy  
- Matplotlib  
- TensorFlow  
- tqdm  

---

## Examples
- Negative of a grayscale image:  
  ![Example Negative](docs/negative.png)  

- Histogram equalization results:  
  ![Histogram Equalization](docs/histogram.png)  

- CNN Training Accuracy:  
  ![CNN Training](docs/cnn_training.png)  

*(Add actual images/screenshots in the `docs/` folder for better visuals.)*

---

## License
This project is licensed under the **MIT License** – feel free to use and modify.  
