# Sentinel-1 SAR Oil Spill Image Analysis

Exploratory Data Analysis (EDA) of Sentinel-1 SAR images to study differences between oil-spill and non-oil-spill images.

## Objectives
- Analyse class distribution.
- Visualise sample images.
- Calculate pixel intensity statistics.
- Identify unusual images using the IQR method.

## Dataset
- Non-Oil Spill: 3,695 images
- Oil Spill: 1,843 images
- Total: 5,538 images

## Technologies
- Python
- NumPy
- Pandas
- Matplotlib
- OpenCV
- Jupyter Notebook

## Repository Structure
```text
sentinel-1-oil-spill-eda/
├── oil_spill_eda.ipynb
└── README.md
```

## Results
Non-oil images showed higher average pixel intensity and standard deviation. Both classes contained outliers, and their statistical distributions overlapped.

## Conclusion
This project explores the visual and statistical characteristics of Sentinel-1 SAR images. It focuses on EDA and does not perform oil-spill prediction or classification.
