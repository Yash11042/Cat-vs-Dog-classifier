
<img width="1024" height="1024" alt="Gemini_Generated_Image_mgsxydmgsxydmgsx" src="https://github.com/user-attachments/assets/87b972a3-e0e7-49a0-a05c-1af529b34ee6" />


# Cat-vs-Dog- Image classifier
A complete deep learning project using TensorFlow and Keras to classify images of cats vs dogs using both MLP and CNN models.

# Project Overview
This project builds a deep learning model to classify images as cat or dog using the Cats vs Dogs dataset from TensorFlow Datasets.
It includes:

1. Data loading and preprocessing
2. Exploratory visualization
3. Model training (MLP & CNN)
4. Regularization & Callbacks
5. Evaluation & results

The CNN-based approach provides high accuracy and is the recommended final model.

# Dataset
Dataset: cats_vs_dogs (Keggel Datasets)
https://www.kaggle.com/tongpython/nattawut-5920421014-cat-vs-dog-dl

# Model Architecture

#### 1. MultiLayer Perceptron (MLP)
Flattened pixel values → Dense layers → Output layer

Good for demonstration but performs poorly on images.

#### 2. Convolutional Neural Network(CNN) 
 
##### CNN includes:

1. Convolution layers
2. MaxPooling
3. Dropout
4. Dense classifier
5. Softmax output

##### Callbacks Included
  1.  EarlyStopping
  2.  ModelCheckpoint
  3.  ReduceLROnPlateau



