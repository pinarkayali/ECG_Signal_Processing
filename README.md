# ECG Signal Processing and Heart Rate Analysis

## Overview

This project analyzes real ECG signals using Python and the MIT-BIH Arrhythmia Database (Record 100).

## Project Objectives

- Visualize ECG signals.
- Reduce noise using digital filtering.
- Analyze frequency components using FFT.
- Detect R-peaks.
- Calculate RR intervals.
- Estimate heart rate (BPM).

## Methods

- **Dataset:** MIT-BIH Arrhythmia Database
- **Filter:** 4th-order Butterworth band-pass (0.5–40 Hz)
- **R-peak Detection:** SciPy `find_peaks`
- **Frequency Analysis:** FFT

## Tools and Libraries

Python, NumPy, SciPy, Matplotlib, WFDB, Google Colab.

## Limitations

The R-peak detection method uses fixed parameters and has not yet been validated against expert annotations. This project is for educational purposes and is not intended for medical diagnosis.

## Dataset

MIT-BIH Arrhythmia Database: https://physionet.org/content/mitdb/1.0.0/
