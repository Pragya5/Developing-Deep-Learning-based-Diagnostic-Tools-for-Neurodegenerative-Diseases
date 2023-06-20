# Developing-Deep-Learning-based-Diagnostic-Tools-for-Neurodegenerative-Diseases
Neurodegenerative diseases pose a significant burden on the healthcare systems, making research aimed at developing techniques
for the early diagnosis of such pathologies, of utmost importance.
Alzheimer’s disease (AD) is a prominent example with millions of
patients affected globally. The detection of the biomarkers of AD
that mark its early progression has been known to aid researchers
in devising notable treatment regimens and testing their efficacy.
Advancements in non-invasive MRI techniques may facilitate the
identification of the biomarkers that are critical for the accurate
diagnosis of AD. Multivariate pattern analysis has been a go-to strategy to effectively analyze neuroimaging data by adopting machine
learning algorithms that extract information from multiple points
in the images without prior knowledge of the points encoding this
information.

## 1. Problem Identification:
Neurodegenerative diseases pose a significant burden on the healthcare systems, making research aimed at developing techniques for the early diagnosis of such pathologies, of utmost importance. Alzheimer’s disease (AD) is a prominent example with millions of patients affected globally. The detection of the biomarkers of AD that mark its early progression has been known to aid researchers in devising notable treatment regimens and testing their efficacy.

## 2. Importance of the Problem:
Millions of people suffer from Alzheimer's disease globally. According to various research papers available online, the average rate of a survival of person suffering from AD is 9 years.

## 3. Methodology
This can be done through the following steps:
Loading the dataset: dataset of differnt brain MRI images have been taken from kaggle that have been labeled into the 4 classes.

1. Preprocessing: Preprocess the images to make them suitable for analysis. This may include cropping, resizing, normalizing the intensity values, etc.

2. Feature Extraction: Extract relevant features from the images that can help differentiate between the classes. This can be done using various techniques such as edge detection, gradient calculation, etc.

3. Model Selection: Select an appropriate machine learning model for the classification problem. Some popular models for image classification include Convolutional Neural Networks (CNNs), Support Vector Machines (SVMs), and Random Forests.

4. Model Training: Train the selected model on the preprocessed images and extracted features.

5. Model Validation: Validate the model's performance on a separate set of images that were not used in the training process.

6. Model Deployment: Finally, deploy the model to make predictions on new, unseen images.

# 4. Approach Followed:
There will be two primary aspects to this project. Identification and classification of Alzheimer's disease.

# 4. a) Detection
Detection models will assess the test data to determine whether this person's brain image exhibits indicators of Alzheimer's disease. In order to determine which type of machine learning model performs the best, we will examine a variety of ML models starting with Detection methods like:

Principle Component Analysis (PCA)
Linear Discriminant Analysis (LDA)
Support Vector Machine with three different kernels, starting with linear to rbf kernel
Convolutional Neural Network models VGG16 for Detection
and Finally Classification using Convolutional Neural Network EfficientNetB0 for Classification

# 5. b) Classification
On the other side, Alzheimer classification will be carried out using data that has been trained with various levels of Alzheimer severity. In fact, this is the method used to create the original data, and this model can also be used as a detector. Doctors may use the ML model as a supplemental tool to help them identify Alzheimer's disease because it will tell them what stage the patient is in. It sheds some insight on the real world since it may identify early stages of AD, which can be treated to prolong life and improve quality of life.

# 6. Dataset Description
[ https://www.kaggle.com/datasets/tourist55/alzheimers-dataset-4-class-of-images ]
