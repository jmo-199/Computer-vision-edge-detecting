
# Project_2

## Name: Jason Moore
## Programming Language: Python v3.9.13
## Date: 10/22/2024

## Description:
This notebook performs image processing tasks, including computing gradient magnitude and orientation using Sobel filters, 
and detecting circles in images using the Hough Circle Transform technique. The project demonstrates key techniques in 
image analysis and feature detection.

### Required Files:
- 1.png: Used for gradient magnitude and orientation calculations.
- 2-1.png
- 2-2.png
- train.mat
- train.png: Input image for circle detection in training.
- test.png: Input image for circle detection in testing.

### Required Packages:
- `cv2` (OpenCV) for image processing
- `matplotlib` for plotting images
- `numpy` for numerical operations
- `scipy` for applying Gaussian smoothing and other filters

### Execution:
1. Ensure you have the necessary image files (1.png, train.png, test.png) in the notebook's directory.
2. Install the required dependencies with:
   ```bash
   pip install opencv-python matplotlib numpy scipy
   ```
3. Open the notebook and execute the cells in sequence to process the images and detect circles.

### Output Files:
- The notebook will display the processed images, including the smoothed image, gradient magnitude, and circle detections.
- Console output will list the coordinates and radii of the detected circles.
