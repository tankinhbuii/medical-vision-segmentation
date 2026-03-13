# Medical Vision Segmentation 🧬🧠

A state-of-the-art Deep Learning pipeline designed for high-precision medical imaging tasks, with a focus on **Lumbar Spine Degenerative Classification** and **RSNA 2024** research.

## 🌟 Overview
Medical images (DICOM) require specialized preprocessing and architecture. This repository implements a robust U-Net / SegFormer pipeline to handle volumetric data and multi-class classification.

## 🚀 Key Features
- **DICOM Preprocessing:** Built-in loaders for medical imaging formats with windowing and normalization.
- **Multi-Planar Reconstruction (MPR):** Analyzing Sagittal, Coronal, and Axial views for better classification accuracy.
- **UNet++ / SegFormer Architectures:** High-precision segmentation for anatomical structures.
- **Kaggle Optimized:** Training and validation loops optimized for large datasets and GPU efficiency.

## 🛠️ Tech Stack
- **Languages:** Python, CUDA.
- **Libraries:** PyTorch, Albumentations, pydicom, Monai.

## 🚀 Usage
```bash
pip install -r requirements.txt
python train.py --config config/spine_classification.yaml
```