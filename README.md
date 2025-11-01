Multimodal Retinal Disease Detection using Deep Learning

This project uses deep learning to detect retinal diseases from multimodal images such as fundus photographs and OCT scans. By combining features from different imaging types, the model improves accuracy in diagnosing conditions like Diabetic Retinopathy, Glaucoma, and Age-related Macular Degeneration (AMD). The goal is to support faster and more reliable eye disease detection.

Features

Multimodal input combining Fundus and OCT images

Deep learning-based classification using CNN or Transformer architectures

Enhanced accuracy through feature fusion

Disease visualization using Grad-CAM

Compatible with datasets such as ODIR, REFUGE, or custom clinical data

Tech Stack

Python

TensorFlow or PyTorch

OpenCV

NumPy, Pandas, Matplotlib

How It Works

Data Preprocessing: Images from multiple modalities are cleaned and resized.

Feature Extraction: CNN extracts visual features from each modality.

Fusion: Multimodal features are combined into a shared representation.

Classification: The model predicts disease categories based on fused features.

Visualization: Grad-CAM highlights the important retinal regions influencing predictions.

Objective

To build an AI-assisted diagnostic system that helps ophthalmologists detect retinal diseases efficiently and accurately, improving clinical decision-making and accessibility to eye care.
