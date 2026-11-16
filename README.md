# ECG Signal Processing and Heart Rate Analysis

## Overview

This project focuses on processing and analyzing real ECG signals using Python. The MIT-BIH Arrhythmia Database is used as the data source.

## Objectives

- Load and visualize ECG signals.
- Apply digital filtering to reduce noise.
- Analyze frequency components using FFT.
- Detect R-peaks.
- Calculate RR intervals.
- Estimate heart rate (BPM).

## Methods

- **Dataset:** MIT-BIH Arrhythmia Database (Record 100)
- **Filtering:** Butterworth band-pass filter (0.5–40 Hz)
- **Peak Detection:** SciPy `find_peaks`
- **Frequency Analysis:** Fast Fourier Transform (FFT)
- **Programming Language:** Python

## Libraries

- NumPy
- SciPy
- Matplotlib
- WFDB

## Tools

Google Colab and GitHub.

## Limitations

The R-peak detection method uses fixed parameters and has not yet been validated against expert annotations. This project is intended for educational purposes and is not a medical diagnostic tool.

## Dataset Reference

Moody, G. B., & Mark, R. G. (2001). The impact of the MIT-BIH Arrhythmia Database. *IEEE Engineering in Medicine and Biology Magazine*.

Dataset: https://physionet.org/content/mitdb/1.0.0/
