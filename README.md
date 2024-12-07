# Hybrid-Images_CV

# 1 Hybrid Image Generator

  This repository provides a Python-based implementation for generating hybrid images, where the low-frequency details of one image are merged with the high-frequency          elements of another, creating a fascinating visual effect. The project utilizes OpenCV for image processing and is optimized for execution in Google Colab.

# 2 Features

_1 Creating Low-Frequency Images:_ Applies a Gaussian blur to smooth the image and generate its low-frequency representation.

_2 Building Hybrid Images:_ Combines the low-frequency components of one image with the high-frequency features of another to create a hybrid image.

_3 Extracting High-Frequency Details:_ Isolates the fine details of an image by subtracting the blurred version from the original.

_4 Display Functionality:_ Uses cv2_imshow in Google Colab to display the processed images directly.
_5 File Saving:_ Saves the resulting low-frequency, high-frequency, and hybrid images as .jpg files for later use.

# 3 Usage

_1 Clone the repository or copy the script._

_2 Replace the paths to your images in the script:_

                  image1_path = '/path/to/image1.png' # Replace with the first image path  
                  image2_path = '/path/to/image2.png' # Replace with the second image path  
_3 Execute the script in Google Colab or any Python environment with OpenCV installed.

_4 The following output files will be created:_
            low_freq_image.jpg
            high_freq_image.jpg
            hybrid_image.jpg


# Requirements

1 Python 3.x
2 OpenCV
3 NumPy
4 Google Colab (optional but recommended for better visualization)





