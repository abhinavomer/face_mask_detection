# Mask Prediction Model

This Python script demonstrates how to use a pre-trained deep learning model to predict whether a person in an image is wearing a mask or not. The script loads the pre-trained model, reads an input image, makes predictions, and prints the predicted class label.

## Usage

1. **Install Dependencies**: Make sure you have the required dependencies installed. You can install them using pip:

pip install opencv-python tensorflow numpy

2. **Download Pre-trained Model**: Download the pre-trained mask prediction model and save it as "mask_prediction.h5".

3. **Run the Script**: Run the Python script "mask_prediction.py" and specify the input image path.

python mask_prediction.py

4. **View Predictions**: The script will display the input image and print the predicted class label to the console, where 0 represents "without mask" and 1 represents "with mask".

## Files

- **mask_prediction.py**: Python script for mask prediction.
- **mask_prediction.h5**: Pre-trained deep learning model for mask prediction.
- **mask_image.jpg**: Sample input image for testing.

## Requirements

- OpenCV (cv2)
- TensorFlow (tf.keras)
- NumPy

## Acknowledgements

The pre-trained model used in this script was trained on a dataset of images with and without masks. Special thanks to the creators of the dataset and TensorFlow for providing tools for deep learning model development.
