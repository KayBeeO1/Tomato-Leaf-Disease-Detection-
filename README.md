# Tomato-Leaf-Disease-Detection-

Introduction
This project focuses on the development of a machine learning model to detect and classify diseases in tomato plants from leaf images. Utilizing a diverse dataset of tomato leaves, the model aims to accurately identify various diseases affecting tomatoes, helping farmers and agriculturists take timely actions to protect their crops.

Dataset
The dataset used for this project is the "Plant_leave_diseases_dataset_without_augmentation" from Medley. It contains approximately 5000 images, each depicting different states of tomato leaves:

Healthy leaves
Leaves affected by various diseases
Background images without leaves
The specific classes in the dataset include:

Tomato (Bacterial spot, Early blight, Late blight, Leaf Mold, Septoria leaf spot, Spider mites Two-spotted spider mite, Target Spot, Yellow Leaf Curl Virus, Mosaic virus, healthy)
Background without leaves
Project Structure
The project is structured as follows:

markdown
Copy code
project-directory/
│
├── data/
│   ├── Tomato___Bacterial_spot/
│   ├── Tomato___Early_blight/
│   ├── Tomato___Late_blight/
│   ├── Tomato___Leaf_Mold/
│   ├── Tomato___Septoria_leaf_spot/
│   ├── Tomato___Spider_mites_Two-spotted_spider_mite/
│   ├── Tomato___Target_Spot/
│   ├── Tomato___Yellow_Leaf_Curl_Virus/
│   ├── Tomato___Mosaic_virus/
│   ├── Tomato___healthy/
│   ├── Background_without_leaves/
│
├── notebooks/
│   ├── data_preprocessing.ipynb
│   ├── model_training.ipynb
│   ├── model_evaluation.ipynb
│
├── src/
│   ├── data_loader.py
│   ├── model.py
│   ├── train.py
│   ├── evaluate.py
│
├── README.md
├── requirements.txt
├── .gitignore
└── LICENSE
Data Preprocessing
Before training the model, several preprocessing steps were applied to the dataset:

Splitting the dataset into training, validation, and test sets
Removing background images
Augmenting the dataset to increase the variety and number of training samples (if applicable)
Model
The model used for this project is based on convolutional neural networks (CNNs), which are well-suited for image classification tasks. The architecture includes multiple convolutional layers followed by pooling layers, and fully connected layers for classification.

Training
The training process involves:

Loading the preprocessed dataset
Initializing the model architecture
Defining the loss function and optimizer
Training the model over several epochs
Validating the model on a separate validation set
Evaluation
The model's performance is evaluated using standard metrics such as accuracy, precision, recall, and F1-score on the test set. Confusion matrices and ROC curves are also used to visualize the performance across different classes.

Results
The trained model achieved the following results:

Overall accuracy: XX%
Precision: XX%
Recall: XX%
F1-score: XX%
These results demonstrate the model's capability to effectively identify and classify various tomato diseases from leaf images.

Usage
