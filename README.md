# RetinaVision: Ocular Disease Classification & Segmentation using YOLOv12

## Project Overview
This project presents a robust deep learning system designed to identify and segment multiple ocular diseases from retinal fundus images. By leveraging the **YOLOv12 segmentation architecture**, the model provides real-time localization and classification of:
- **Age-Related Macular Degeneration (AMD)**
- **Cataract**
- **Pathologic Myopia**

**Read the full paper on ResearchGate:** [Classifying and Segmenting Multiple Ocular Diseases Using Deep Learning Based on Retinal Imaging](https://www.researchgate.net/publication/403377182)

## Key Features
- **Architecture:** Implementation of the latest YOLOv12 model with attention-based feature extraction.
- **Multi-Task Learning:** Simultaneous classification and instance segmentation of ocular abnormalities.
- **Performance:** Trained over 606 epochs, achieving high mean Average Precision (mAP) for disease localization.
- **Publication:** Formalized research published and available for academic review.

## Methodology
- **Dataset:** The RetinaVision dataset, consisting of curated and annotated fundus images.
- **Preprocessing:** 80-10-10 split for training, validation, and testing; image augmentation via Roboflow.
- **Training:** Conducted using Google Colab with custom anchors and cross-scale fusion for fine-structure detection.

## Performance & Testing
The model demonstrates strong generalization on unseen test data. Detailed evidence of model performance, including prediction masks and confidence scores (e.g., 88% - 94% confidence for Pathologic Myopia), can be found in the `Evidence of model testing.pdf`.

## Project Structure
- `Latest_Final.ipynb`: The primary notebook containing Roboflow integration and YOLOv12 training.
- `IEEE Paper Final.pdf`: The technical paper detailing the research and architecture.
- `Evidence of model testing.pdf`: Visual results and performance metrics from the testing phase.
- `requirements.txt`: Dependencies for reproducing the environment.

## Citation
If you use this research or code in your work, please cite it as:
> Panugan III, F. M., Refulle, L. E., Villamil, P. J., & Baldo, N. G. (2026). *Classifying and Segmenting Multiple Ocular Diseases Using Deep Learning Based on Retinal Imaging*. ResearchGate. DOI: 10.13140/RG.2.2.33333.3333 (Update with actual DOI if available).

## Authors
- **Felipe M. Panugan III** - Mapúa University
- **Liandro E. Refulle** - Mapúa University
- **Prince Jeffery Villamil** - Mapúa University
- **Nicko Gabriel Baldo** - Mapúa University
