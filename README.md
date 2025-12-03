# Landslide Detection using Deep Learning & Geospatial Analysis

This project implements **Landslide Detection** from satellite imagery using a modified **U-Net architecture** enhanced with **Attention**, **Deep Supervision**, and **ConvLSTM** modules.  
It combines **deep learning**, **geospatial data processing**, and **semantic segmentation** to accurately detect landslide-prone regions.

---

## Key Features
-  Custom **U-Net architecture** implemented in `UNet.py`
-  Supports **Attention Gate**, **Autoencoder Mode**, **Deep Supervision**, **Bi-ConvLSTM**
-  Works with **GeoTIFF satellite imagery**
-  Custom metrics: **Precision, Recall, F1-score** (in `utils.py`)
-  Notebook included: `DL_Spatial_Project.ipynb`
-  Trained model weights included: `best_model.h5`


## Dataset:
https://www.kaggle.com/datasets/tekbahadurkshetri/landslide4sense
