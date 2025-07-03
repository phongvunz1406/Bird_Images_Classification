
# Bird Image Classification using Transfer Learning

This project focuses on fine-grained image classification of bird species using convolutional neural networks and transfer learning. With over 200 bird classes, the goal is to build a robust classifier that accurately identifies the species from an image.

## Project Structure

- `Bird_img_classification.ipynb`: Jupyter notebook containing all the steps for data loading, preprocessing, model training, evaluation, and visualization.
- `README.md`: This file.

## Dataset

The dataset used is a multi-class bird species image dataset consisting of:
- 200 unique bird species
- Thousands of labeled images
- Organized into training, validation, and test folders


## Features

- Data augmentation to improve generalization
- Transfer learning using pretrained CNN models (ResNet50)
- Training, validation, and test set evaluation
- Visualizations of training metrics and predictions

## Dependencies

Install required libraries using pip:

```bash
pip install tensorflow keras matplotlib seaborn numpy scikit-learn
```

Jupyter Notebook is required to run the notebook file interactively.

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/yourusername/bird-image-classification.git
cd bird-image-classification
```

2. Launch the notebook:

```bash
jupyter notebook Bird_img_classification.ipynb
```

3. Make sure the dataset is correctly placed and the paths inside the notebook are properly configured.

## Goals

- Understand the application of transfer learning to fine-grained image classification
- Improve performance by tuning pretrained models
- Evaluate classification models with meaningful metrics

## Results

- Achieved high accuracy on the test set (update with actual results)
- Effective feature extraction and generalization using transfer learning

## License

This project is licensed under the MIT License.

## Author

[Vu Thanh Phong]  
(https://github.com/phongvunz1406)
