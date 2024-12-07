# Hybrid-Images_CV

# 1 Hybrid Image Generator

  This repository provides a Python-based implementation for generating hybrid images, where the low-frequency details of one image are merged with the high-frequency          elements of another, creating a fascinating visual effect. The project utilizes OpenCV for image processing and is optimized for execution in Google Colab.

# 2 Features

__Creating Low-Frequency Images:__ Applies a Gaussian blur to smooth the image and generate its low-frequency representation.
Extracting High-Frequency Details: Isolates the fine details of an image by subtracting the blurred version from the original.
Building Hybrid Images: Combines the low-frequency components of one image with the high-frequency features of another to create a hybrid image.
Display Functionality: Uses cv2_imshow in Google Colab to display the processed images directly.
File Saving: Saves the resulting low-frequency, high-frequency, and hybrid images as .jpg files for later use.

Usage

Clone the repository or copy the script.
Replace the paths to your images in the script:
python
Copy code
image1_path = '/path/to/image1.png'  # Replace with the first image path  
image2_path = '/path/to/image2.png'  # Replace with the second image path  
Execute the script in Google Colab or any Python environment with OpenCV installed.
The following output files will be created:
low_freq_image.jpg
high_freq_image.jpg
hybrid_image.jpg
Requirements

Python 3.x
OpenCV
NumPy
Google Colab (optional but recommended for better visualization)





