GPU vs CPU image processing benchmark using CUDA and Numba.

The project was developed and executed in the Google Colab environment with enabled CUDA GPU acceleration.

This project compares the performance of CPU and GPU implementations of basic image processing algorithms:
- Mean Filter
- Gaussian Blur
- Sobel Edge Detection

The goal of the project is to demonstrate parallel image processing using CUDA and analyze performance scaling for different image sizes.

Technologies: Python, CUDA, Numba, NumPy, Matplotlib, OpenCV

GPU benchmarks were performed using the GPU environment available in Google Colab.

## Features
- CPU implementations using Numba JIT
- GPU implementations using CUDA kernels
- Parallel image processing
- CPU vs GPU benchmarking
- Scaling benchmark for different image resolutions
- GPU speedup visualization

## Algorithms
Mean Filter

Simple averaging filter used for image smoothing and noise reduction.

Gaussian Blur

Weighted blur filter using Gaussian kernel for more natural smoothing.

Sobel Edge Detection

Gradient-based edge detection algorithm used to highlight image contours.

## Benchmark

The project benchmarks CPU and GPU execution times for image sizes:
- 256×256
- 512×512
- 1024×1024
- 2048×2048
- 4096×4096

## Example Visualizations
The project generates:
- filtered images,
- edge detection results,
- scaling benchmark plots,
- GPU speedup charts.
