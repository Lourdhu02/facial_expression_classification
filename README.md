# Facial Expression Classification

This repository contains the code and data for a facial expression classification project using Convolutional Neural Networks (CNNs). The dataset and pre-trained model are included as zip files.

## Table of Contents

- [Project Description](#project-description)
- [Dataset](#dataset)
- [Model](#model)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Description

This project aims to classify facial expressions into different categories using a CNN model. The dataset consists of images of faces with various expressions, and the model has been trained to recognize these expressions.

## Dataset

The dataset used for training and testing is included in this repository as a zip file. 

- `FER_Custom_Dataset.zip`: Contains the images used for training and testing the model.

## Model

A pre-trained model is included for inference.

- `model.zip`: Contains the saved CNN model (`model.h5`) which can be used for prediction.

## Setup Instructions

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Lourdhu02/facial_expression_classification.git
   cd facial_expression_classification
   ```

2. **Unzip the Dataset and Model:**

   Unzip the `dataset.zip` and `model.zip` files to extract the contents.

   ```bash
   unzip dataset.zip
   unzip model.zip
   ```

3. **Install Dependencies:**

   Install the required Python packages using `pip`:

   ```bash
   pip install -r requirements.txt
   ```

   If you don't have a `requirements.txt` file, you can create one with the necessary dependencies:

   ```txt
   tensorflow
   opencv-python
   numpy
   matplotlib
   ```

   Then, install the packages:

   ```bash
   pip install tensorflow opencv-python numpy matplotlib
   ```


### Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

### License

This project is licensed under the MIT License.
```

### Notes:
- Replace `'class1', 'class2', 'class3'` in the live detection script with your actual class names.
- Make sure the paths in the setup and usage sections match your directory structure.
- If you have a `requirements.txt` file, include it in your repository to help users install the dependencies easily.

Feel free to customize this README as needed for your specific project. Let me know if you need any more information or assistance!
