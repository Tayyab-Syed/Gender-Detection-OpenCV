# Gender Detection from Facial Images

This repository includes a Python script for predicting the gender of individuals in facial images using a deep-learning model. The script utilizes Convolutional Neural Networks (CNNs) and employs the Caffe framework for gender estimation.

## Setup and Requirements
### Requirements
- OpenCV (cv2)
- Caffe model files for age estimation and face detection
- Python 3.x

### Setup Instructions
#### 1. Clone the repository:
```
git clone https://github.com/Tayyab-Syed/Gender-Detection-OpenCV
```

#### 2. Install Dependencies:
```
pip install opencv-python numpy
```
#### 3. Download Weights for Model:
- [Google Drive](https://drive.google.com/drive/folders/1p2GOMGMj1kjU7SxkNYWWxtAWyNSkpmdW?usp=sharing)

## Usage
Run the code in the terminal:
```
python gender-detection.py
```
## Results
The script displays the input image with bounding boxes around detected faces and their corresponding predicted gender labels. Predicted gender probabilities for "Male" and "Female" are printed in the console.

The processed image with gender predictions is saved as predicted_gender.jpg in the same directory.

## Example

![Output](https://github.com/Tayyab-Syed/Gender-Detection-OpenCV/blob/main/Gender-Detection/predicted_gender.jpg)
