# ECG-Image-to-CSV-Converter
Converts scanned or photographed ECG images into clean, normalized CSV signals for analysis and machine learning
https://colab.research.google.com/drive/1pN_ZsdIuKV-krGjQ1c26u1i07bHJL1Ie?usp=sharing 
this is the link to colab :)

# Overview
This project reads scanned or photographed ECG images and converts them into digital ECG signals. The processed signals are smoothed, normalized, and saved as a CSV file, ready for plotting or future machine learning analysis.
# Features
- Reads ECG images (JPEG, PNG, etc.)
- Extracts the ECG waveform from the image
- Smooths the signal using Savitzky-Golay filter
- Normalizes the signal (0 to 1)
- Saves the digital signal to a CSV file
- Plots the original and processed ECG for visualization
# Why This Is Useful
- Converts ECG images to numeric data, enabling analysis without manual digitization
- Prepares data for future ML projects (e.g., arrhythmia detection)
- Beginner-friendly introduction to signal processing and data preparation
## Requirements
- Python 3.8+
- Libraries: OpenCV, NumPy, Matplotlib, SciPy, Pandas
