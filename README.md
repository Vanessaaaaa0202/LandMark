# Landmark Image Classification with Transfer Learning

In this project, I developed a landmark classification model using transfer learning techniques to address the limitations of a small dataset. The model leveraged the pre-trained VGG16 convolutional neural network to mitigate overfitting and enhance generalizability.

## Overview

- **Transfer Learning**: Utilized the VGG16 model as a base to build upon learned features.
- **Data Augmentation**: Applied random cropping, flipping, rotation, and color adjustments to increase dataset diversity.
- **Model Architecture**: Added a flatten layer followed by two fully connected dense layers to adapt the feature extraction for the task.
- **Training**: Trained the model for 500 epochs, achieving a validation accuracy of over 90%.

## Skills Demonstrated

- Transfer Learning
- Data Augmentation
- Convolutional Neural Networks (CNN)
- TensorFlow & Jupyter Notebook

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/yourusername/landmark-classification.git
   cd landmark-classification
   ```

2. Install the required dependencies:

   ```sh
   pip install -r requirements.txt
   ```

## Usage

- Run the notebook to train the model:

   ```sh
   jupyter notebook landmark_classification.ipynb
   ```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
