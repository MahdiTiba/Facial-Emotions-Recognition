# Facial Emotions Recognition

This project focuses on recognizing facial emotions using deep learning techniques. The repository contains code and resources to train and evaluate models for facial emotion recognition tasks.

## Table of Contents

- [Dataset](#dataset)
- [Model Architectures](#model-architectures)
- [Training](#training)
- [Evaluation](#evaluation)
- [Usage](#usage)
- [License](#license)

## Dataset

The dataset used in this project is stored in the file `5-celebrity-faces-dataset.npz`. This dataset contains images of five different celebrities, which are used to train and evaluate the facial emotion recognition models.

## Model Architectures

The project employs several deep learning architectures for facial emotion recognition:

1. **AlexNet**: A pre-trained AlexNet model is utilized and saved as `AlexNet-model.h5` in the repository.

2. **InceptionResNetV1**: This architecture combines the Inception module with residual connections to efficiently extract facial features. The implementation is provided in the `inception_resnet_v1.py` file.

3. **FaceNet**: FaceNet is a deep convolutional network designed by Google to map faces into a high-dimensional space, where distances directly correspond to a measure of face similarity. The pre-trained FaceNet model is saved as `facenet_keras.h5` in the repository.

## Training

The training process involves the following steps:

1. **Data Preparation**: Loading and preprocessing the images from the dataset.

2. **Model Compilation**: Configuring the models with appropriate loss functions and optimizers.

3. **Model Training**: Training the models on the prepared dataset.

The training processes for different models are documented in the following Jupyter Notebooks:

- `Facial_emotions_recognition.ipynb`: Details the training of the AlexNet model.

- `Face-Recognition.ipynb`: Documents the training process using the FaceNet model.

- `Change-in-Facial-Mode.ipynb`: Explores the training using the InceptionResNetV1 architecture.

## Evaluation

The trained models' performances are evaluated using various metrics to assess their accuracy in recognizing facial emotions. Evaluation details are included in their respective notebooks.

## Usage

To use the facial emotion recognition models:

1. Clone the repository:

   ```bash
   git clone https://github.com/MahdiTiba/Facial-Emotions-Recognition.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Facial-Emotions-Recognition
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the Jupyter Notebooks:

   ```bash
   jupyter notebook <notebook_name>.ipynb
   ```

   Replace `<notebook_name>` with the desired notebook to explore the training and evaluation processes.

## License

This project is licensed under the MIT License. For more details, refer to the `LICENSE` file in the repository.
