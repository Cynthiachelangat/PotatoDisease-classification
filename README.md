# Potato Disease Classification API

This project is an API designed to classify potato leaf images into one of three categories: **Early Blight**, **Late Blight**, or **Healthy**. 

### Features:
- **Image Classification**: Upload a potato leaf image, and the model predicts whether the leaf is affected by Early Blight, Late Blight, or is Healthy.
- **REST API**: The API is built using FastAPI, making it easy to integrate with other applications.
- **Confidence Score**: Along with the classification, the API returns a confidence score indicating the model's certainty.

### Technologies Used:
- **FastAPI**: For building the API.
- **TensorFlow**: For loading and running the trained deep learning model.
- **PIL and NumPy**: For image processing.

### Endpoints:
- **/ping**: A simple health check endpoint.
- **/predict**: Endpoint to upload an image and receive a classification.

This project provides a streamlined way to automate the classification of potato leaf diseases, helping farmers and agricultural experts make informed decisions quickly.
