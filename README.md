# OpenCV Image Augmentation Lab

This project demonstrates fundamental image augmentation techniques using OpenCV in Python.  
It is built as a step-by-step practical notebook for understanding basic computer vision transformations.

---

## 📌 Overview

The notebook performs various image transformations such as:

- Grayscale conversion
- Image rotation
- Image slicing (cropping)
- Flipping
- Resizing
- Blurring
- Padding
- Brightness and contrast adjustment
- Gaussian blur
- Median blur
- Shearing transformation
- Color jitter (random brightness and contrast)

This project is ideal for beginners learning computer vision and image preprocessing for machine learning.

---

## 🛠 Technologies Used

- Python
- OpenCV (cv2)
- NumPy
- Google Colab (for visualization)

---

## 🔍 Image Augmentation Techniques Implemented

## 1. Image Loading
- Load image using cv2.imread()

## 2. Grayscale Conversion
- Convert BGR image to grayscale using cv2.cvtColor()

## 3. Image Rotation
- Rotate image (e.g., 180 degrees) using cv2.rotate()

## 4. Cropping (Image Slicing)
- Extract Region of Interest (ROI) using array slicing

## 5. Flipping
- Flip image horizontally or vertically using cv2.flip()

## 6. Resizing
- Resize image to desired dimensions using cv2.resize()

## 7. Averaging Blur
- Apply smoothing using cv2.blur()

## 8. Gaussian Blur
- Apply Gaussian smoothing using cv2.GaussianBlur()

## 9. Median Blur
- Reduce noise using cv2.medianBlur()

## 10. Padding
- Add border around image using cv2.copyMakeBorder()

## 11. Brightness Adjustment
- Modify pixel intensity using cv2.convertScaleAbs()

## 12. Contrast Adjustment
- Adjust contrast using alpha parameter in cv2.convertScaleAbs()

## 13. Shearing (Affine Transformation)
- Apply affine transformation using cv2.warpAffine()

## 14. Color Jitter
- Apply random brightness and contrast using NumPy + cv2.convertScaleAbs()
