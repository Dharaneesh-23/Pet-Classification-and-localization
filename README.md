# Pet-Classification-and-localization
# Project Overview
 - This project utilizes a Convolutional Neural Network (CNN) to classify 37 breeds of cats and dogs and accurately predict bounding boxes for pet localization using the Oxford IIIT Pet dataset. The model achieves a classification accuracy of 69.17% and a bounding box mean squared error (MSE) of 0.4155 on the validation set.

# Dataset
 - The Oxford IIIT Pet dataset is used for training and evaluating the model. This dataset includes images of 37 breeds of pets, with annotations for breed classification and bounding box localization.

# Model Architecture
The CNN model consists of the following layers:

 - Input layer for images of size 128x128 with 3 color channels (RGB)
 - Convolutional layers with increasing filter sizes and ReLU activation
 - MaxPooling layers to reduce spatial dimensions
 - Flatten and Dense layers for classification and bounding box regression

# Key Features
 - Classification Accuracy: 69.17%
 - Bounding Box MSE: 0.4155
 # Data Preprocessing
 - Image Resizing with Padding: Ensures consistent input size while preserving aspect ratio.
 - Bounding Box Normalization: Scales coordinates to fit within the resized image dimensions.
 - Data Augmentation: Enhances the model's generalization capabilities.

# Installation
1. Clone the repository:
```bash
git clone https://github.com/dharaneesh-23/pet-classification-and-localization.git
```
2. Navigate to the project directory
```bash
cd pet-classification-localization
```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
  ```
