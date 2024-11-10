# Hand Sign Recognition with TensorFlow

This project uses a deep learning model to recognize American Sign Language (ASL) hand signs in real time through a webcam feed. The model is trained on the ASL Alphabet dataset and deployed with TensorFlow and OpenCV.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Dependencies](#dependencies)

## Project Overview

The Hand Sign Recognition project classifies ASL hand gestures using a Convolutional Neural Network (CNN) trained on the [ASL Alphabet dataset](https://www.kaggle.com/datasets/grassknoted/asl-alphabet). The project captures live images from a webcam and predicts the corresponding hand sign in real-time.

## Dataset

The model is trained on the ASL Alphabet dataset, using the first 1500 images of each class. The training configuration includes:
- **Epochs**: 50
- **Batch Size**: 32
- **Image Size**: 200x200 pixels

## Setup Instructions

### Prerequisites

- Python 3.10
- Clone the repository:

   ```bash
   git clone https://github.com/yourusername/hand-sign-recognition.git
   cd hand-sign-recognition

### Installing Dependencies


