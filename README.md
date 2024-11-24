# Terrain Matching with SSIM

This repository demonstrates how to use **Structural Similarity Index (SSIM)** and **2D Correlation** to match a smaller terrain area to a larger map. It includes a multi-resolution approach for faster and more accurate matching, and simulates real-world scenarios by adding noise to the observed area.

## Features

- **SSIM Matching**: Uses SSIM to measure the similarity between the real area and the large raster.
- **2D Correlation Example**: Simple implementation of terrain matching using `correlate2d`.
- **Multi-Resolution Optimization**: Speeds up the matching process by downsampling and refining at full resolution.
- **Noise Simulation**: Adds Gaussian noise to the smaller area to simulate real-world conditions.
- **Visualization**: Highlights the real area, noisy area, matched area, and correlation scores for better understanding.

## Requirements

Install the required libraries using `pip`:

```bash
pip install numpy matplotlib scikit-image pillow scipy
```
