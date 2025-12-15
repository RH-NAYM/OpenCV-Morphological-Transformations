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
This project provides a comprehensive, practical exploration of Morphological Transformations using `OpenCV` in Python.
Morphological operations are a core building block in computer vision pipelines, especially for `noise removal`, `shape refinement`, `gap filling`, and `structural analysis` of binary and grayscale `images`.

They are most commonly used after thresholding and before contour detection, OCR, or object segmentation.

---

The `Jupyter Notebook` demonstrates key morphological operations including:
- Erosion
- Dilation
- Opening
- Closing
- Morphological Gradient
- Top Hat
- Black Hat

Each operation includes:
- Mathematical intuition and visual explanation.
- Practical OpenCV implementations.
- Step-by-step visualizations using Matplotlib.
- Real-world preprocessing strategies for OCR, document detection, and segmentation.

`Whether you are learning image morphology for the first time or building production CV pipelines, this repository serves as a solid reference and reusable toolkit.`

# 📁 Project Structure
```bash
.
├── 📓 Opencv-Morphological-Transformations.ipynb   # Comprehensive notebook on morphology
├── 📘 README.md                                    # Project documentation & overview
├── 📦 requirements.txt                             # Python dependencies
├── 🖼️ testImage.jpg                                # Sample image for demonstrations
└── 🛠️ tools                                        # Utility module for image handling
    ├── __pycache__                                  # Python cache directory (auto-generated)
    │   └── tools.cpython-312.pyc
    └── tools.py                                     # Helper functions for loading & visualization
```

# 📋 Table of Contents (Notebook Sections)
---
```bash
1. Introduction to Morphological Image Processing
2. Structuring Elements (Kernels)
3. Erosion
4. Dilation
5. Opening (Erosion → Dilation)
6. Closing (Dilation → Erosion)
7. Morphological Gradient
8. Top Hat Transformation
9. Black Hat Transformation
10. Combining Morphology with Thresholding
11. Visual Comparisons and Analysis
12. Best Practices and Kernel Selection
```

# 🧠 What You’ll Learn
---
- **Erosion:** Shrink foreground regions and remove small white noise.
- **Dilation:** Expand foreground regions and fill gaps.
- **Opening:** Remove noise while preserving object structure.
- **Closing:** Fill small holes and connect broken components.
- **Morphological Gradient:** Extract object boundaries.
- **Top Hat:** Highlight small bright regions on dark backgrounds.
- **Black Hat:** Highlight small dark regions on bright backgrounds.
- **Kernel Engineering:** Choosing kernel size and shape (`RECT`, `ELLIPSE`) for different tasks.
- **Pipeline Design:** How morphology fits into OCR, document detection, and segmentation workflows.

# 🛠️ Technologies Used
---
- `Python 3.x`
- `OpenCV` for morphological image processing
- `NumPy` for array operations
- `Matplotlib` for visualization
- `Jupyter Notebook` for interactive experimentation

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
- Open `Opencv-Morphological-Transformations.ipynb` and run cells sequentially.
    - Notebook will automatically download a placeholder image if testImage.jpg is missing.


**Option 2: Google Colab**
- Upload `Opencv-Morphological-Transformations.ipynb` to Colab.
- Install dependencies: `!pip install -r requirements.txt`.
- Run all cells for interactive demonstrations.


# ✅ Summary
---
- Morphological transformations are essential for cleaning and refining binary images.
- They significantly improve results for `OCR`, `contour detection`, and `segmentation`.
- Kernel size and shape directly affect output quality.
- Combining thresholding + morphology yields robust preprocessing pipelines.
- The notebook provides a reusable framework for both learning and production use.



# 🍴 Real-World Applications
---
- **OCR Preprocessing:** Clean text regions before recognition.
- **Document Detection:** Close gaps and extract document boundaries.
- **Industrial Vision:** Remove noise and isolate objects.
- **Medical Imaging:** Refine segmented regions.
- **Satellite & Aerial Imagery:** Enhance terrain or structure masks.
- **Retail Analytics:** Shelf, POSM, and planogram segmentation.

# 📝 Contribution
`Feel free to open an issue or submit a pull request to improve examples, add kernel experiments, or extend the morphological pipelines.`
