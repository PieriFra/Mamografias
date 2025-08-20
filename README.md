# Mammography Classification

This repository contains a deep learning model for classifying mammogram images. The goal is to assist in the detection of breast cancer by distinguishing between benign, malignant, and normal cases. The model uses a Convolutional Neural Network (CNN) trained on a publicly available dataset.

## Features

- **Classification Model:** A CNN designed for image classification.
- **Dataset:** Utilizes a dataset of mammogram images with labels for benign, malignant, and normal cases.
- **Preprocessing:** Includes scripts for data augmentation and normalization to improve model performance.
- **Training:** Provides a training pipeline to fine-tune the model.
- **Evaluation:** Scripts for evaluating the model's accuracy, precision, and recall.

## Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/PieriFra/Mamografias.git](https://github.com/PieriFra/Mamografias.git)
    cd Mamografias
    ```

2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1.  **Prepare the data:** Place your mammogram images in the `data/raw` folder. The folder structure should be `data/raw/{benign, malignant, normal}`.

2.  **Run the training script:**
    ```bash
    python train.py
    ```

3.  **Evaluate the model:**
    ```bash
    python evaluate.py
    ```
