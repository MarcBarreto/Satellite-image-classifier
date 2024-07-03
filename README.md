# Satellite Image Classifier

## Table of Contents
1. [Introduction](#introduction)
2. [Project Structure](#project-structure)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Model](#model)
6. [Data](#data)
7. [License](#license)

## Introduction
This project focuses on classifying satellite images using a convolutional neural network (CNN) developed with PyTorch. The entire workflow, from data preprocessing to model deployment, is contained in a single Jupyter notebook, designed to be executed on Google Colab.

## Project Structure
The project is organized as follows:
```sh
satellite-image-classifier
┣ 📜 satellite_image_classifier.ipynb
┗ 📜 README.md
```


## Installation
To run this project, you need to have Google Colab set up. Follow the instructions below to get started:

1. **Open Google Colab**: Go to [Google Colab](https://colab.research.google.com/).

2. **Upload the Notebook**:
   - Click on `File` > `Upload notebook`.
   - Choose the `satellite_image_classifier.ipynb` file from your local machine.

3. **Set Up the Environment**:
   - Ensure you have a Google account to save and execute the notebook.

## Usage
To use the satellite image classifier, follow these steps:

1. **Load the Dataset**:
   - The dataset used for training and testing the model is EuroSAT_RGB. It can be accessed from [this link](https://huggingface.co/datasets/blanchon/EuroSAT_RGB).

2. **Execute the Notebook**:
   - Run each cell in the `satellite_image_classifier.ipynb` notebook sequentially.
   - The notebook includes the following steps:
     - Data preprocessing
     - Model creation
     - Model training
     - Model evaluation
     - Model deployment

## Model
### Convolutional Neural Network (CNN)
- **Framework**: PyTorch
- **Description**: The notebook `satellite_image_classifier.ipynb` contains the entire pipeline for building, training, and evaluating the CNN model designed for satellite image classification.

## Data
The dataset used in this project is EuroSAT_RGB, which contains labeled satellite images. The dataset can be found and downloaded from [Hugging Face](https://huggingface.co/datasets/blanchon/EuroSAT_RGB).

## License
This project is licensed under the GPL-3.0 License. See the [LICENSE](https://www.gnu.org/licenses/gpl-3.0.en.html) file for more information.

---

Feel free to explore the notebook and experiment with different configurations to see how the model performs!
