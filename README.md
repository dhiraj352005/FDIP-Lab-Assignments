# Digital Image Processing – Assignment No. 1 

This repository contains  implementation of **basic image enhancement techniques** using Python, OpenCV, NumPy, and Matplotlib.  
The code is written in a Jupyter Notebook and demonstrates how different transformations affect an image.  

---

## Techniques Implemented
- Brightness Improvement  
- Brightness Reduction  
- Thresholding  
- Negative Transformation  
- Logarithmic Transformation  
- Power-Law (Gamma) Transformation  

---

## Requirements
- Python 3.x  
- OpenCV (`pip install opencv-python`)  
- NumPy (`pip install numpy`)  
- Matplotlib (`pip install matplotlib`)  

---

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/DIP-Assignment1.git
   cd DIP-Assignment1



    Output Preview
The notebook displays the following results for the input image:

Original grayscale image

Brightness ↑ / ↓

Thresholded binary image

Negative transformation

Logarithmic transformation

Gamma corrected image

Each result is shown both visually (images) and numerically (pixel values).

 # Applications
 
Medical imaging (X-ray enhancement)

Photography and image editing

Remote sensing image analysis

Preprocessing for computer vision tasks





Digital Image Processing – Assignment 2
This assignment focuses on understanding histogram equalization and applying different filters in both the spatial and frequency domains. The implementation is done in Python using OpenCV, NumPy, and Matplotlib.

Tasks Implemented
Histogram Operations
The program begins by reading a grayscale image and plotting its histogram. Histogram equalization is then applied to improve the contrast of the image. After equalization, the histogram becomes more evenly spread, which makes the details in both dark and bright regions clearer and easier to see.

Spatial Domain Filters
Several spatial filters are applied to the image:

The mean or average filter smooths the image and reduces random noise, though it also blurs the edges.

The Gaussian filter also smooths the image but preserves edges better compared to the mean filter.

The median filter is especially useful for removing salt-and-pepper noise while maintaining sharp edges.

A sharpening filter is used to highlight fine details and edges, although it may also make noise more visible.

Frequency Domain Filters
The image is also processed in the frequency domain using Fourier transforms.

Low pass filtering reduces high frequency components, which results in a smoother image.

High pass filtering emphasizes high frequency components, making edges and fine details more visible.

Band pass filtering allows only a certain range of frequencies to pass, which can balance between smoothing and edge enhancement.

Requirements
The implementation requires Python 3 along with OpenCV, NumPy, and Matplotlib.

How to Run
Clone the repository and open the Jupyter Notebook. Running the notebook will display the input image, its histogram, the equalized image, and the results of applying each filter.

Output Preview
The outputs include the original grayscale image, its histogram before and after equalization, and the results of applying both spatial and frequency domain filters. Each result is shown visually and can be compared with the original image to understand how the transformation changes its appearance.

Applications
These techniques are widely used in real life. Histogram equalization is applied in medical imaging to improve the visibility of X-rays and MRI scans. Filters are used in photography for noise removal and sharpening. Remote sensing makes use of these methods for analyzing satellite images, and in computer vision they are often used as preprocessing steps for tasks like edge detection and object recognition.
