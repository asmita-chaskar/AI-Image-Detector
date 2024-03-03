# AI Image Detector

AI Image Detector is a web application that uses a pre-trained deep learning model to classify images uploaded by users.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [File Structure](#file-structure)
- [License](#license)

## Introduction

The AI Image Detector project is a Flask-based web application that allows users to upload images and get predictions from a pre-trained deep learning model. The model is loaded using Keras and predicts the top class label for the uploaded image.

## Installation

1. Clone the repository:

- git clone https://github.com/asmita-chaskar/AI-Image-Detector.git

## Usage

1. Run the Flask application:

- python app.py

2. Open a web browser and go to `http://localhost:5000` to access the application.

3. Upload an image using the provided form and click on the "Predict!" button to get the classification result.

## Technologies Used

- Python
- Flask
- TensorFlow
- Keras
- HTML/CSS
- Bootstrap

## File Structure

- `app.py`: Flask application file containing routes and model prediction logic.
- `vgg19.h5`: Pre-trained VGG19 model file.
- `uploads/`: Directory to store uploaded images.
- `static/`: Directory containing static files (CSS, JavaScript).
- `templates/`: Directory containing HTML templates.