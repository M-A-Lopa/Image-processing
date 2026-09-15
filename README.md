# Image Processing

Labs, tasks, and assignments from **CSE428 (Image Processing)**, covering classical image processing techniques and their extension into machine learning and deep learning for image analysis.

## Contents

### Image Processing Fundamentals
| File | Description |
|---|---|
| `Lab_1_Intro_to_NumPy_Arrays_and_Digital_Images.ipynb` | Basics of representing and manipulating images as NumPy arrays. |
| `Task_1_Basic_Image_Operations_and_Histogram.ipynb` | Practice with basic image operations and histograms. |
| `Lab_2_Point_Processing_and_Histogram_Equalization.ipynb` | Contrast stretching, log/power-law transforms, and histogram equalization. |
| `Task_3_Edge_Detection_and_Localized_Histeq.ipynb` | Edge detection (Sobel) and localized histogram equalization. |
| `Lab_4_DFT_and_Frequency_Domain_Filtering.ipynb` | Discrete Fourier Transform, sampling, aliasing, and frequency-domain filtering. |
| `2D_FFT_and_Frequency_Domain_Filtering.ipynb` | Applying 2D FFT on an image and reconstructing low-pass/high-pass/band-pass filtered versions. |
| `Assignment_1_Image_Enhancement_and_Spatial_Filtering.ipynb` | Combined assignment on image enhancement, histogram equalization, and spatial/frequency filtering. |

### Machine Learning & Deep Learning for Images
| File | Description |
|---|---|
| `Lab_5_Linear_and_Logistic_Regression.ipynb` | Introduction to linear and logistic regression. |
| `Task_5_Logistic_Regression_Digit_Classification.ipynb` | Logistic regression applied to digit classification. |
| `Lab_6_Intro_to_Neural_Networks_with_PyTorch.ipynb` | Building basic neural networks with PyTorch. |
| `Lab_7_Image_Classification_with_NN_and_CNN.ipynb` | Image classification using neural networks and CNNs. |
| `Lab_8_UNet_Breast_Ultrasound_Segmentation.ipynb` | U-Net based image segmentation on breast ultrasound scans. |
| `Assignment_2_Logistic_Regression_vs_CNN_CIFAR10.ipynb` | Comparing logistic regression and CNNs for CIFAR-10 image classification. |

## Datasets Used
- Boston Housing Dataset
- Wisconsin Breast Cancer Dataset
- California Housing Dataset
- MNIST
- Digits Dataset (scikit-learn)
- CIFAR-10
- BUS-UCLM Breast Ultrasound Lesion Segmentation Dataset

## Tools & Libraries
NumPy, OpenCV, scikit-image, Matplotlib, scikit-learn, TensorFlow/Keras, PyTorch

## How to Run
Each notebook is self-contained — open it in Jupyter or Google Colab and run the cells in order. Some notebooks expect a dataset image (e.g. `brain_mri.png`, `cat.png`) to be present in the working directory or Colab's `/content/` folder; check the notebook's first few cells for the expected filename.

## Note
These notebooks were completed as part of coursework and are shared here for personal reference and learning.
