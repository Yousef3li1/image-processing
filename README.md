# 🖼 Image Preprocessing with OpenCV

## 🌟 Overview

This project demonstrates the basic steps of image preprocessing using **OpenCV**. The notebook provides functions for:
- Loading images
- Converting to grayscale
- Applying Gaussian blur
- Detecting edges with Canny edge detection
- Denoising with median blur

These techniques are commonly used in computer vision applications to prepare images for further analysis or feature extraction.

---

## ✨ Features

- **Grayscale Conversion**: Convert the image to grayscale for easier analysis.
- **Gaussian Blur**: Smoothens the image to remove noise and reduce detail.
- **Canny Edge Detection**: Detects edges in the image for feature extraction.
- **Median Blur**: Further reduces noise and sharpens the image.

---

## 🛠 Components

This project uses the following tools:
- **OpenCV**: For image manipulation and preprocessing.
- **Python**: For writing the image processing functions.
- **Jupyter Notebook**: For interactive development and testing.

---

## ⚙️ Setup

1. **Install Dependencies**:
   Install the necessary Python packages using pip:

   ```bash
   pip install opencv-python matplotlib


 ## 🧑‍💻 Code Explanation

The main functions used in this notebook are:

### 1. `load_image(image_path)`
   Loads an image from the given path and checks if the file exists and the image is valid.

### 2. `convert_to_grayscale(image)`
   Converts the loaded image into grayscale, which simplifies further image processing tasks.

### 3. `apply_gaussian_blur(image)`
   Applies Gaussian blur to the grayscale image to smooth it and reduce noise.

### 4. `apply_canny_edge_detection(image)`
   Uses the Canny edge detection algorithm to identify edges in the image.

### 5. `apply_median_blur(image)`
   Applies median blur to reduce noise and sharpen the image after edge detection.

---

## ⚡ How to Use

1. **Load your image**:  
   Update the `image_path` variable with the path to your image.

2. **Run the functions**:  
   Execute the notebook cells to preprocess your image. The results will be displayed at each stage of the process.

3. **View Results**:  
   The notebook will display the processed images at each step (grayscale, blurred, edges, denoised).

---

## 🔍 Example Workflow

1. **Load Image**:  
   Load an image from your local machine or an online source.

2. **Convert to Grayscale**:  
   Convert the image to grayscale for better processing.

3. **Apply Gaussian Blur**:  
   Smooth the image to reduce noise.

4. **Edge Detection**:  
   Detect the edges using the Canny edge detector.

5. **Denoise**:  
   Apply median blur to the edge-detected image for denoising.

---

## ⚠️ Notes

- Ensure the image file path is correctly set.
- The image should be in a compatible format (e.g., PNG, JPG).
- You can modify the kernel sizes and parameters for blurring and edge detection to fine-tune the results based on your use case.

