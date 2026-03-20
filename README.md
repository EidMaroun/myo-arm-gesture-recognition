# Myo Arm Gesture Recognition

A notebook-based machine learning project for recognizing arm and hand gestures from **Myo armband EMG signals**.

This repository explores an end-to-end experimental workflow for **preprocessing EMG recordings**, preparing datasets under multiple conditions, and training traditional machine learning classifiers for gesture recognition. The project is organized as a research-style workflow in Jupyter notebooks rather than as a packaged Python module, making it especially suitable for experimentation, iteration, and academic demonstration.

---

## Overview

This project focuses on **gesture recognition using Myo armband sensor data**. The repository contains multiple notebooks that cover:

- preprocessing raw EMG data
- handling alternative dataset variants
- training classification models
- comparing experiments with and without specific signal values retained
- consolidating the pipeline in broader “all-in-one” notebooks
- presenting the work in poster format

The current repository structure suggests an iterative experimentation process in which preprocessing and training were tested across different scenarios, especially around **including or excluding zero-valued samples**.

---

## Repository Structure

```bash
myo-arm-gesture-recognition/
├── Poster Presentation.pdf
├── code.ipynb
├── everything.ipynb
├── preprocessing_with_0s.ipynb
├── preprocessing_without_0s.ipynb
├── train2.ipynb
├── train4.ipynb
├── training_with_0s.ipynb
└── training_without_0s.ipynb
