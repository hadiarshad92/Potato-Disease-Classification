# Potato Disease Classification

## Overview

Potato Disease Classification is a web-based application that allows users to upload a photo of a potato plant, and the backend model classifies the image to detect potential diseases. The project is designed to assist farmers and agricultural experts in diagnosing plant diseases early.

## Tech Stack

- **Frontend**: React.js
- **Backend**: FastAPI (Python)
- **Machine Learning Framework**: TensorFlow
- **Dataset**: PlantVillage
- **Model Type**: Convolutional Neural Network (CNN)

## Features

- Users can upload an image of a potato plant.
- The backend processes the image and classifies it into healthy or diseased categories.
- The model is trained on the PlantVillage dataset to recognize various potato diseases.
- FastAPI provides a lightweight and efficient API for model inference.
- Responsive and user-friendly frontend built with React.js.

## Model Details

- The model is built using **TensorFlow and Keras**.
- It is trained with a **CNN architecture** optimized for image classification.
- The dataset is preprocessed and split into training, validation, and test sets.
- It undergoes **20 epochs of training** for optimal accuracy.
- The classification results are returned via an API endpoint in JSON format.

## Deployment

- The frontend and backend are deployed as separate services.
- The FastAPI backend is hosted with an inference server to serve predictions.
- The React.js frontend consumes the API to display classification results in real-time.

## Future Enhancements

- Improve model accuracy with data augmentation techniques.
- Deploy the model on cloud-based GPU services for faster inference.
- Implement a history log for users to track previous classifications.
- Add support for more plant diseases beyond potatoes.

## How to Use

1. Upload an image of a potato plant via the web interface.
2. The backend processes the image and classifies the disease.
3. View the classification result along with confidence scores.

## Installation & Setup

### Backend (FastAPI)

```bash
pip install fastapi uvicorn tensorflow
uvicorn main:app --reload
```

### Frontend (React.js)

```bash
npm install
npm start
```
