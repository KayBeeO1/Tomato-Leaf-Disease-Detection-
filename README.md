# Tomato-Leaf-Disease-Detection

## Introduction
This project focuses on developing a machine learning model to detect and classify diseases in tomato plants from leaf images. Utilizing a diverse dataset of tomato leaves, the model aims to accurately identify various diseases affecting tomatoes, helping farmers and agriculturists take timely actions to protect their crops.

## Dataset
The dataset used for this project is the "Plant_leave_diseases_dataset_without_augmentation" from Medley. It contains approximately 5000 images, each depicting different states of tomato leaves:

- **Healthy leaves**
- **Leaves affected by various diseases**
- **Background images without leaves**

The specific classes in the dataset include:

- **Tomato Diseases:**
  - Bacterial spot
  - Early blight
  - Late blight
  - Leaf Mold
  - Septoria leaf spot
  - Spider mites (Two-spotted spider mite)
  - Target Spot
  - Yellow Leaf Curl Virus
  - Mosaic virus
  - Healthy

- **Background without leaves**

## Data Preprocessing
Before training the model, several preprocessing steps were applied to the dataset:

1. **Splitting the dataset** into training, validation, and test sets.
2. **Removing background images** to focus on the relevant data.
3. **Augmenting the dataset** to increase the variety and number of training samples (if applicable).

## Model
The model used for this project is based on convolutional neural networks (CNNs), which are well-suited for image classification tasks. The architecture includes multiple convolutional layers followed by pooling layers and fully connected layers for classification.

## Training
The training process involves:

1. **Loading the preprocessed dataset**
2. **Initializing the model architecture**
3. **Defining the loss function and optimizer**
4. **Training the model over several epochs**
5. **Validating the model on a separate validation set**

## Evaluation
The model's performance is evaluated using standard metrics such as accuracy, precision, recall, and F1-score on the test set. Confusion matrices and ROC curves are also used to visualize the performance across different classes.

## Results
The trained model achieved the following results:

- **Overall accuracy:** XX%
- **Precision:** XX%
- **Recall:** XX%
- **F1-score:** XX%

These results demonstrate the model's capability to effectively identify and classify various tomato diseases from leaf images.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any changes or enhancements.
