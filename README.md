# NMR Data Analysis Project 🧑‍🔬

This project processes and analyzes **13C NMR** spectra from raw data files. It uses Python with libraries like `numpy`, `matplotlib`, and `scipy` to clean, visualize, and extract information from the spectra.

---

## 📚 Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Usage](#usage)


---

## 📖 Introduction

This repository contains a Python-based tool for analyzing **Nuclear Magnetic Resonance (NMR)** data, specifically **13C NMR**. The script processes raw data in `.txt` format, performs peak detection, and visualizes the spectrum.

### 🎯 Main Goals:
- Process 13C NMR data from raw text files.
- Perform peak detection and visual representation of the spectrum.
- Identify and annotate peaks with ppm values.

---

## 🚀 Features

- **Data Filtering**: Filters out low-intensity data points to focus on the most relevant peaks.
- **Peak Detection**: Uses `scipy` to automatically detect and annotate peaks in the spectrum.
- **Interactive Visualization**: Generates high-resolution plots of the NMR spectrum using `matplotlib`.
- **Modular Code**: Easily extendable for other types of NMR or additional data processing.

---

## 🛠️ Technologies Used

- Python 3.x
- `numpy`: For numerical operations
- `matplotlib`: For plotting and visualization
- `scipy`: For peak detection
- Jupyter Notebooks: For interactive development and analysis

---

## 🏃‍♂️ Usage

1. Place your NMR `.txt` file in the `data` folder.
2. Open the Jupyter notebook:
    ```bash
    jupyter notebook
    ```
3. Run the notebook and see the results for NMR data analysis and visualization.

**Note**: The `file_path` in the notebook is set to `data/13C_NMR.020.001.1r.txt`, adjust it according to your data files.

---
