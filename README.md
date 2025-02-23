# Cat and Dog Categorization Project

## Overview
This project classifies images into two categories: **Cat** and **Dog**. It uses a machine learning model and Keras for image processing and prediction. The model processes input images, predicts their category, and outputs either "Cat" or "Dog."

## Requirements
- Python 3.x
- Keras (with TensorFlow as backend)
- NumPy
- Matplotlib

To install the required libraries, run the following command:

```bash
pip install keras numpy matplotlib
```

## Key Steps
### Image Loading and Preprocessing:

The input image is loaded, resized to 200x200 pixels, and converted into a NumPy array.
The array dimensions are expanded to match the model’s input shape.

### Model Prediction:

The pre-trained model predicts whether the image is of a cat or a dog by outputting a probability value between 0 and 1.
If the result is greater than or equal to 0.5, the image is classified as a dog. Otherwise, it is classified as a cat.

### Mapping the Result:

The numerical result is mapped to the corresponding category ("Dog" or "Cat").
Usage
Place the image (e.g., cat.jpg) in the working directory.
Load the pre-trained model (or train a model if needed).
Run the script to get the classification output.

## Conclusion
This project demonstrates a simple approach to image classification using deep learning. It highlights how easy it is to classify images into categories like "Cat" or "Dog" using pre-trained models and Keras' image processing tools. 
