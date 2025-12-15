# 🖼️ Comprehensive Image Thresholding in OpenCV
---
[![dev branch](https://img.shields.io/badge/branch-dev-red?style=flat&logo=git&logoColor=white)](https://github.com/RH-NAYM/OpenCV-Image-Thresholding/tree/dev)
#

<p align="center">
  <a href="https://opencv.org/" target="_blank">
    <img src="https://img.shields.io/badge/OpenCV-Computer%20Vision-green?logo=opencv&logoColor=white">
  </a>
  <a href="https://www.python.org/" target="_blank">
    <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white">
  </a>
  <a href="https://jupyter.org/" target="_blank">
    <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white">
  </a>
  <a href="https://numpy.org/" target="_blank">
    <img src="https://img.shields.io/badge/Numpy-Numerical-lightblue?logo=numpy&logoColor=white">
  </a>
  <a href="https://matplotlib.org/" target="_blank">
    <img src="https://img_0.png">
  </a>
</p>



# 📌 Overview
This project provides a detailed exploration of image thresholding techniques using `OpenCV` in Python. Thresholding is a fundamental technique in image processing, used to segment objects, extract features, and prepare images for further analysis like OCR or object detection.

---

The `Jupyter Notebook` demonstrates `Simple (Global) Thresholding`, `Adaptive Thresholding`, and `Otsu's Binarization`, including:
- Theoretical explanations and mathematical formulations.
- Practical OpenCV implementations.
- Step-by-step visualizations using Matplotlib.
- Tips for preprocessing, noise reduction, and optimal threshold selection.

`Whether you are new to computer vision or need a reference for image segmentation, this repository provides an end-to-end guide.`

# 📁 Project Structure
```bash
.
├── 📓 Image-Thresholding-OpenCV.ipynb   # Comprehensive Jupyter Notebook on image thresholding
├── 📘 README.md                          # Detailed documentation & project overview
├── 📦 requirements.txt                   # Python dependencies (OpenCV, NumPy, Matplotlib)
├── 🖼️ testImage.jpg                        # Sample image for demonstrations
└── 🛠️ tools                              # Utility module for image handling
    ├── __pycache__                        # Python cache directory (auto-generated)
    │   └── tools.cpython-312.pyc          # Compiled Python cache file
    └── tools.py                           # Functions for loading, converting, and displaying images
```

# 📋 Table of Contents (Notebook Sections)
---
```bash
1. Introduction to Image Thresholding
2. Simple (Global) Thresholding
3. Adaptive Thresholding
    - Mean Method
    - Gaussian Method
4. Otsu's Binarization
5. Preprocessing for Thresholding
    - Median Blur
    - Gaussian Blur
6. Combining Thresholding with Noise Reduction
7. Visual Comparisons and Analysis
8. Best Practices and Recommendations
```

# 🧠 What You’ll Learn
---
- **Simple Thresholding:** `Binary`, `Binary Inverse`, `Trunc`, `ToZero`, `ToZero Inverse`.
- **Adaptive Thresholding:** Handling `non-uniform` illumination using `mean` or `Gaussian` local thresholds.
- **Otsu’s Binarization:** `Automatic threshold selection` for bimodal histograms.
- **Preprocessing:** Use of `Median blur` and `Gaussian blur` to reduce noise before thresholding.
- **Visual Analysis:** Compare results across multiple thresholding methods with `Matplotlib`.
- **Practical Tips:** Choosing `threshold values`, `block sizes`, and `constants` for adaptive methods.
- **Application Insights:** `Image segmentation` for `OCR`, `object detection`, and `feature extraction`.

# 🛠️ Technologies Used
---
- `Python 3.x`
- `OpenCV` for core image processing.
- `NumPy` for array manipulation.
- `Matplotlib` for plotting and visualization.
- `Jupyter Notebook` for interactive execution.

# 📦 Installation
---
## 1️⃣ Create a virtual environment
```bash
python -m venv venv
source venv/bin/activate    # Linux / macOS
venv\Scripts\activate       # Windows
```
## 2️⃣ Install dependencies
```bash
pip install -r requirements.txt
```
# 🚀 How to Run
---
**Option 1: Jupyter Notebook (Local)**
- Install Jupyter if needed: `pip install notebook`.
- Launch Jupyter: `jupyter notebook`.
- Open `Image-Thresholding-OpenCV.ipynb` and run cells sequentially.
    - Notebook will automatically download a placeholder image if testImage.jpg is missing.


**Option 2: Google Colab**
- Upload `Image-Thresholding-OpenCV.ipynb` to Colab.
- Install dependencies: `!pip install -r requirements.txt`.
- Run all cells for interactive demonstrations.


# ✅ Summary
---
- Thresholding is a key tool for image segmentation and preprocessing in computer vision.
- `Simple`, `adaptive`, and `Otsu methods` cover a wide range of scenarios.
- Preprocessing with `blur` filters improves results for `noisy` or `unevenly lit` images.
- `Matplotlib` visualizations help in intuitive understanding and parameter tuning.
- The notebook provides a reusable framework for applying thresholding in various applications.



# 🍴 Real-World Applications
---
- **OCR Preprocessing:** Prepare scanned documents for `text` recognition.
- **Medical Imaging:** Segment regions of interest in `X-rays` or `MRI` scans.
- **Object Detection:** Separate foreground from background in industrial or surveillance systems.
- **Photography:** Extract `silhouettes`, `masks`, or `feature regions` from images.
- **Satellite Imagery:** Detect `terrain` features and `land/water` segmentation.


# 📝 Contribution
`Feel free to open an issue or submit a pull request to improve the notebook, add examples, or extend the thresholding techniques.`
