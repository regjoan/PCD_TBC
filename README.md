# MachineTB-Vision: Tuberculosis Detection on Chest X-Ray Images

## Overview
MachineTB-Vision is a machine learning pipeline developed for detecting tuberculosis (TB) from chest X-ray (CXR) images using lung region segmentation and feature extraction. The system processes CXR images through several stages, including lung region segmentation using a *crop method*, followed by feature extraction using Histogram of Oriented Gradients (HOG), and classification using machine learning models like Support Vector Machine (SVM) and Random Forest.

This approach focuses on improving TB detection by segmenting the lung regions and performing classification on a focused area, reducing noise and irrelevant features from the entire image.

### Keywords:
Tuberculosis detection, chest X-ray imaging, lung segmentation, machine learning, deep learning, feature extraction, HOG, Random Forest, SVM, crop method.

## Video Presentation

Here’s the link to the project video presentation:

[Project Video Presentation](https://drive.google.com/file/d/1276Eeaxq0Y6mr494F7IqH8E2xeLmMQOe/view?usp=sharing)


## Authors
- Radithya Farrel Fauzan (23/516311/PA/22089) - [radithyafarrelfauzan@mail.ugm.ac.id](mailto:radithyafarrelfauzan@mail.ugm.ac.id)
- Arya Jason Ramadhanto (24/536944/PA/22780) - [aryajasonramadhanto@mail.ugm.ac.id](mailto:aryajasonramadhanto@mail.ugm.ac.id)
- Regina Joan Medea Jati Laksono (24/532850/PA/22546) - [reginajoanmedeajatilaksono@mail.ugm.ac.id](mailto:reginajoanmedeajatilaksono@mail.ugm.ac.id)
- Nareswari Ayu Prabowo (24/532991/PA/22558) - [nareswariayuprabowo@mail.ugm.ac.id](mailto:nareswariayuprabowo@mail.ugm.ac.id)

## Project Description
**MachineTB-Vision** automates the detection of tuberculosis (TB) from chest X-ray (CXR) images using lung segmentation and machine learning models. The lung segmentation step uses a *crop method*, where the lung regions are isolated from the full CXR image to reduce irrelevant information. This segmentation process is followed by feature extraction using Histogram of Oriented Gradients (HOG), and classification is performed using Support Vector Machine (SVM) and Random Forest algorithms.

The system provides a reliable and efficient tool for TB detection in low-resource settings, where access to trained radiologists may be limited.

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-repository/MachineTB-Vision.git
cd MachineTB-Vision
