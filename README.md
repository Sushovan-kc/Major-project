# *Major-project*
## *Brain Hemorrhage Segmentation using Supervised and Self-Supervised Learning*
### *Overview*

This repository contains code for automatic segmentation of brain hemorrhages from CT/MRI scans using both supervised and self-supervised learning (SSL) techniques. The project aims to reduce manual annotation effort and improve segmentation accuracy by leveraging unlabeled data alongside labeled datasets.

### *Features*

Supervised segmentation using U-Net architecture.

Self-supervised pretraining using Masked Autoencoders (MAE) to learn robust representations from unlabeled brain scans.

Fine-tuning pretrained encoder for hemorrhage segmentation.

Visualization of predicted masks over input scans.

Designed for limited labeled data scenarios common in medical imaging.

### *Dataset*

CT or MRI brain scans with hemorrhage annotations.

Preprocessing includes resizing, normalization, and augmentations (rotations, flips, noise).

### *Methodology*

Data Preprocessing: Convert images, normalize intensities, apply augmentations.

Self-Supervised Pretraining: Train encoder on unlabeled scans for feature extraction.

Supervised Segmentation: Fine-tune encoder with decoder on labeled dataset.

Evaluation: Dice coefficient, IoU, precision, recall.

Optional Deployment: Flask/Streamlit app for clinical demonstration.

### *Technologies*

Python, TensorFlow/Keras or PyTorch

OpenCV, NumPy, Albumentations

Matplotlib, Seaborn for visualization


###*Results*

Accurate segmentation of brain hemorrhage regions.

Demonstrates how SSL improves performance with limited labeled data.
