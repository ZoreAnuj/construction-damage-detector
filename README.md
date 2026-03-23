# Construction Damage Detector

This project implements computer vision models to automatically detect and segment structural damages in construction imagery. It aims to assist in building inspections by identifying defects like cracks and corrosion, enabling faster and more consistent assessments.

## Key Features
*   Implements deep learning models (U-Net, Mask R-CNN) for semantic and instance segmentation of damages.
*   Includes data preprocessing and augmentation pipelines for construction image datasets.
*   Provides model training scripts and evaluation metrics (IoU, Dice Score) to benchmark performance.

## Tech Stack
Python, PyTorch, OpenCV, scikit-learn, Matplotlib

## Getting Started
1.  Clone the repo: `git clone https://github.com/zoreanuj/construction-damage-detector.git`
2.  Install dependencies: `pip install -r requirements.txt`
3.  Run a training example: `python train.py --config configs/unet_config.yaml`