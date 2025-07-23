# Bird Species Classification – CUB-200-2011 Dataset

This project focuses on identifying bird species using image classification techniques with the CUB-200-2011 dataset. 
A Convolutional Neural Network (CNN) was implemented using TensorFlow and Keras to build and train the model.

## Overview

- Preprocessed image data (resizing, normalization)
- Built a CNN using Keras and PyTorch
- Trained on the CUB-200-2011 dataset containing images of 200 different bird species
- Evaluated model performance using accuracy metrics
- Visualized training history and prediction outputs

## Tools and Libraries

- Python
- Jupyter Notebook
- TensorFlow, Keras, PyTorch
- NumPy, Matplotlib, Seaborn
- Scikit-learn

## Dataset

This project uses the CUB-200-2011 dataset, a publicly available image dataset with over 11,000 images across 200 bird species. 
It is commonly used for fine-grained classification tasks.

## Results

The model achieved good accuracy on the validation set and demonstrated potential for bird species recognition using deep learning.

## Known Issue

The final prediction display block throws a `NameError` because `class_names` was not defined.  
This variable is intended to map predicted indices to actual bird names.  
To fix it, define a list like:

```python
class_names = [f"Bird_{i}" for i in range(1, 201)]
```

## How to Run

1. Download and extract the CUB-200-2011 dataset
2. Install required libraries
3. Place the dataset in the expected folder structure (as used in the notebook)
4. Run the notebook in Jupyter or VS Code

## Author

Gulbika Aghamuradova
