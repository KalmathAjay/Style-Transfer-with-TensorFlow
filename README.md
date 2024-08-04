# Style Transfer with TensorFlow

**Style Transfer** is a technique used to apply the artistic style of one image (the "style image") to another image (the "content image"). This results in a new image that retains the content of the  original image while adopting the artistic style of the second image.

## Overview

This project demonstrates how to perform style transfer using TensorFlow and TensorFlow Hub. We use a pre-trained model available on TensorFlow Hub to accomplish this task.

## Requirements

- Python 3.x
- TensorFlow 2.x
- NumPy
- PIL (Pillow)
- Matplotlib
- TensorFlow Hub

## Installation

To install the required packages, you can use `pip`:
```sh
pip install tensorflow numpy pillow matplotlib tensorflow_hub
```

## Usage

1. **Load the Style Transfer Model**: We load a pre-trained model from TensorFlow Hub that can perform arbitrary style transfer.
2. **Load and Preprocess Images**: We load and preprocess the content and style images to prepare them for the model.
3. **Display the Images**: Visualize the original content and style images.
4. **Apply Style Transfer**: We apply the style transfer to the content image using the style image.
5. **Display the Stylized Image**: Show the resulting image that combines the content and style.

## Detailed Steps

1. **Load the Style Transfer Model**

   The pre-trained model used in this project is available on TensorFlow Hub. It can perform arbitrary style transfer by taking in a content image and a style image as inputs and outputting a stylized image.

2. **Load and Preprocess Images**

   The images are loaded from disk and preprocessed to a suitable format for the model. The preprocessing includes resizing the images to a maximum dimension and normalizing pixel values.

3. **Display the Images**

   The original content and style images are displayed side by side to visualize the inputs to the model.

4. **Apply Style Transfer**

   The style transfer model is applied to the content image using the style image. The model combines the content of the first image with the style of the second image to produce a new image.

5. **Display the Stylized Image**

   The resulting stylized image is displayed, showing the content of the original image with the artistic style of the style image.

## Additional Resources

For more details, refer to the following resources:

- [TensorFlow Hub Documentation](https://www.tensorflow.org/hub)
- [TensorFlow Neural Style Transfer Tutorial](https://www.tensorflow.org/tutorials/generative/style_transfer)
