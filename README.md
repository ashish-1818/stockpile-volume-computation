# Stockpile Volume Computation

## Overview
This project estimates stockpile volume using 3D point cloud processing techniques and Open3D.

## Features
- Point cloud preprocessing
- Noise removal
- Plane segmentation using RANSAC
- Stockpile extraction
- Volume estimation

## Technologies Used
- Python
- Open3D
- NumPy
- SciPy
- Matplotlib

## Workflow
1. Load point cloud
2. Remove noise
3. Detect ground plane
4. Separate stockpile
5. Compute volume

## Output
The stockpile was successfully segmented and processed for volume estimation.

## Run Instructions

pip install -r requirements.txt

jupyter notebook

Run:
src/stockpile_volume.ipynb

Sample code for the [Stockpile volume with Open3D](https://jose-llorens-ripolles.medium.com/stockpile-volume-with-open3d-fa9d32099b6f) article 
