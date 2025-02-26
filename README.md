# AI Image Classifier using TensorFlow and Streamlit

## Overview
This project is a simple AI-powered image classifier built using TensorFlow and Streamlit. It allows users to upload an image, and the model predicts its content using the MobileNetV2 pre-trained model.

## Features
- Upload an image in JPG, PNG, or JPEG format.
- Uses MobileNetV2, a pre-trained deep learning model.
- Displays the uploaded image.
- Predicts and shows the top three classification results with confidence percentages.

## Installation
Ensure you have Python installed, then install the required dependencies:

```bash
pip install streamlit tensorflow pillow numpy
```

## Running the Application
To start the Streamlit app, run the following command:

```bash
streamlit run your_script.py
```

Replace `your_script.py` with the actual filename.

## Usage
1. Open the Streamlit app in your browser.
2. Upload an image.
3. The model will analyze and provide predictions.

## Dependencies
- Python
- Streamlit
- TensorFlow
- Pillow
- NumPy

## Notes
- The model used (MobileNetV2) is trained on ImageNet and works best with general object classification.
- For best results, ensure images have clear objects and minimal noise.

## License
This project is for educational and demonstration purposes.

