# Image Segmentation using K-Means Clustering


---

## Overview

The program uses **K-Means clustering** from `scikit-learn` to group the pixels of an image into a specified number of color clusters. The output is a segmented version of the original image where each pixel is replaced with the centroid color of its cluster.

This technique is useful for:

- Image compression
- Object detection preprocessing
- Color-based image analysis

---

## Features

- Simple Python implementation using **NumPy**, **Matplotlib**, and **scikit-learn**.
- Reduces the number of colors in the image to `n_clusters`.
- Provides visual comparison between the **original** and **segmented** image.

---

## Dependencies

Make sure you have Python installed along with the following packages:

- `numpy`
- `matplotlib`
- `scikit-learn`

You can install them using pip:

```bash
pip install numpy matplotlib scikit-learn


Usage

Clone the repository:

git clone <your-repo-url>
cd <repository-folder>


Place your image in the project folder or use the path to your image.

Run the Python script:

python kmeans_image_segmentation.py


The program will:

Display the original image.

Apply K-Means clustering to segment the image.

Display the segmented image with reduced colors.

How it Works

Load Image:
The image is read using matplotlib.pyplot.imread.

Reshape Image for Clustering:
Convert the image from (height, width, 3) to (num_pixels, 3) for clustering.

K-Means Clustering:
Pixels are grouped into n_clusters based on color similarity.

Replace Pixel Colors:
Each pixel is replaced with the color of its cluster center.

Reshape to Original Image:
The clustered pixels are reshaped back to the original image dimensions.

Results

The segmented image reduces the number of colors to n_clusters.

Useful for visualizing dominant colors and simplifying images for further processing.

Author

Ananya Prasad M

MSc in Electronics (AI specialization)
