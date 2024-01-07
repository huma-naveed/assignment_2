
# Assignment 2: Handwritten Digit Classification and Retrieval

## Description
This project tackles the challenge of classifying and retrieving handwritten digits. It encompasses three main tasks: constructing a basic Convolutional Neural Network (CNN) from scratch for digit classification, employing transfer learning with VGG16 to enhance classification, and implementing an image retrieval system to find similar images.

## Installation
No installation is necessary. All tasks are completed in Google Colab, which provides an interactive environment with GPU support.

## Usage
Each Jupyter notebook corresponds to a specific task:
- `CNN_Basic.ipynb`: Basic CNN model for digit classification.
- `Transfer_Learning.ipynb`: Enhancing classification with VGG16 and transfer learning.
- `Image_Retrieval.ipynb`: Implementing an image retrieval system using features extracted by a pre-trained model.

## Approach
### Task 1: Basic CNN for Classification
- Developed a CNN with convolutional, pooling, and dense layers to classify digits.
- Trained and evaluated the model on a dataset of handwritten digits, tuning parameters to improve accuracy.

### Task 2: Transfer Learning with VGG16
- Employed the VGG16 model pre-trained on ImageNet as a feature extractor.
- Replaced the top layers with custom layers tailored for digit classification.
- Fine-tuned the pre-trained model to better adapt to the specifics of the digit dataset.

### Task 3: Image Retrieval System
- Implemented an image retrieval system using the VGG16 model to extract feature vectors from images.
- Compared the feature vectors of a query image against a database of images using Euclidean distance.
- Retrieved and displayed images most similar to the query image, effectively creating a content-based image retrieval system.

## Results
- **Task 1**: The basic CNN model achieved an accuracy of XX%.
- **Task 2**: The VGG16 based model improved classification accuracy to YY%.
- **Task 3**: Successfully implemented an image retrieval system, demonstrating the ability to find and display images similar to a given query.

## Credits
- TensorFlow and Keras documentation for providing comprehensive guides.
- Google Colab for the computing resources.

## License
This project is made available under the [MIT License](https://choosealicense.com/licenses/mit/).

