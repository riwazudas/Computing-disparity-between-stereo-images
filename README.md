# Computing Disparity Between Stereo Images 📷🔍

This repository contains the solution for **COMP90086 Computer Vision, 2024 Semester 2, Assignment 3** at the University of Melbourne. The project focuses on computing the **disparity map** between two stereo images — a fundamental step in estimating the three-dimensional structure of a scene.

---

## Project Overview 🎯
The primary goal of this assignment is to **implement and analyze methods for estimating disparity maps** from stereo image pairs. This involves:

- Understanding and applying concepts related to **image warping** and **disparity estimation**
- Analyzing the impact of various parameters (like **window size**) on the accuracy and quality of the generated disparity maps.

The project utilizes the **Middlebury dataset**, which provides stereo image pairs along with ground truth disparity images and camera calibration information for robust evaluation.

---

## Key Features / Implemented Tasks 🛠️
This project covers the following aspects typical of computer vision stereo disparity estimation:

1. **Baseline Disparity Estimation:**
   - Understanding and explaining **image warping**
   - Analyzing artifacts like **black pixels** resulting from warping
   - Explaining the core logic of disparity estimation
   - Describing and critiquing errors in the estimated disparity map

2. **Effect of Window Size:**
   - Investigation into how different **window sizes** (or scale parameters) influence the quality and characteristics of the computed disparity map.

---

## How to Run the Project ▶️

This project is implemented as a **Jupyter Notebook**, allowing for interactive, step-by-step execution and visualization of results.

---

## Prerequisites ⚙️
Make sure you have the following installed:

- **Python 3.x**
- **Jupyter Notebook**
- Required Python Libraries:
  - `numpy` (numerical operations)
  - `matplotlib` (plotting and visualization)
  - `opencv-python` (image processing)
  - `scipy` (image processing/optimization)

Install dependencies using pip:

```bash
pip install numpy matplotlib opencv-python scipy jupyter
```

## Running the Notebook 📝
- Clone the Repository:
  First, clone this GitHub repository to your local machine:
```
git clone https://github.com/riwazudas/Computing-disparity-between-stereo-images.git
cd Computing-disparity-between-stereo-images
```

- Open Jupyter Notebook:
  Navigate to the project directory in your terminal and start Jupyter Notebook:
```bash
jupyter notebook
```
- Execute the Notebook:
  In the Jupyter Notebook interface that opens in your browser, locate and open the main .ipynb file (e.g., assignment3.ipynb or disparity_estimation.ipynb). You can then run the cells sequentially to execute the   code, view explanations, and observe the results, including the generated disparity maps.

## Data 📂
The assignment utilizes images from the Middlebury dataset. Ensure that the necessary image pairs (e.g., "Backpack" example) are available in the correct directory structure as expected by the Jupyter Notebook. If not included in the repository, you might need to download specific image pairs from the Middlebury stereo dataset website.

## Academic Integrity Warning ⚠️
Please note: This code was developed as part of a university assignment. While it is publicly available, using or submitting this code (or significant portions thereof) for your own academic assignments may constitute academic misconduct as per your institution's policies. Please ensure you understand and adhere to your university's guidelines on plagiarism and academic integrity.

## Assignment Context
This project was completed as part of COMP90086 Computer Vision at the University of Melbourne, Semester 2, 2024.
