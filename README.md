# INT3404: Image Processing
## 2D-3D Retrieval 

## Goal
Implement an image classification problem of Nom characters using a CNN model. The input data includes a set of Nom character images. 
The goal is to build a model capable of accurately classifying the input image into one of the corresponding Nom character classes.
## Description

1. Preprocess images:
- Use transformations to augment data, including flipping images, rotating images, changing brightness, blurring, and sharpening images.
- Extract features from image variants.
2. Prepare data:
- Read label data from a CSV file, including image names and corresponding labels.
- Build a list of features and labels from the read images and labels.
- Split the data into training and testing sets.
3. Build the CNN model:
- Use a CNN model with Conv2D, MaxPooling2D, and Dense layers.
- The number of output layers is 252, corresponding to the number of Nôm character classes to be classified.
4. Train the model:
- Use the training dataset to train the model with a fixed number of epochs.
5. Evaluate the model:
- Evaluate the model's performance on the test set by calculating loss and accuracy.
6. Predict:
Use the trained model to predict the labels of new images.

## Contributors

| Student ID | Full name |
|------|----|
| 20021459 | Trịnh Công Trung |

## Reports
Link to final report: https://docs.google.com/document/d/1C94s19FLESP2Pc4GztbRx_ibWcffDpwKpS_pCqEx8iY/edit?usp=sharing
