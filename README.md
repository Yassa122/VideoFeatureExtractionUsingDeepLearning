# 4NN-CNN Video Extraction

This repository contains a project focused on extracting features from video data using a 4-layer Convolutional Neural Network (CNN). The primary objective is to develop and implement a CNN architecture capable of efficiently processing video frames to extract meaningful features for further applications, such as action recognition, object detection, and video summarization.

## Features
- **4-Layer CNN Architecture**: A well-structured 4-layer CNN designed for robust feature extraction from video data.
- **Frame Preprocessing**: Tools for preprocessing video frames, including resizing, normalization, and augmentation techniques.
- **Training Pipeline**: A comprehensive training pipeline with customizable parameters for learning rate, batch size, and epochs.
- **Evaluation Metrics**: Implementation of various evaluation metrics to assess the performance of the model.
- **Sample Datasets**: Scripts to download and preprocess sample video datasets for training and testing.
- **Inference Module**: A module to perform inference on new video data using the trained CNN model.

## Getting Started
To get started with the project, follow the steps below:

1. **Clone the Repository**
    ```bash
    git clone https://github.com/yourusername/4NN-CNN-Video-Extraction.git
    cd 4NN-CNN-Video-Extraction
    ```

2. **Install Dependencies**
    ```bash
    pip install -r requirements.txt
    ```

3. **Prepare Dataset**
    - Download a sample video dataset and place it in the `data/` directory.
    - Use the provided scripts in the `scripts/` directory to preprocess the dataset.

4. **Train the Model**
    ```bash
    python train.py --config config/train_config.yaml
    ```

5. **Evaluate the Model**
    ```bash
    python evaluate.py --config config/eval_config.yaml
    ```

6. **Run Inference**
    ```bash
    python inference.py --video_path path/to/video.mp4 --output_path path/to/output
    ```

## Project Structure
