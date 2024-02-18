## Leaflet Product Classification
This directory contains a script for training a deep learning model for image classification using TensorFlow and Keras. The model architecture utilizes a pre-trained ResNet50 base model with additional layers for classification. The script performs end-to-end training, including data preprocessing, augmentation, model training, evaluation, and saving

### Model Pipeline

#### Data Preparation and Preprocessing
<p align="justify"> The pipeline begins with downloading a dataset containing images of various classes.
A CSV file is generated to map image names to their respective classes.
Data augmentation techniques are applied to increase the diversity of the training dataset.
The dataset is split into training and validation sets, and the necessary directories are created.</p>

#### Model Building
<p align="justify"> The pipeline uses a pre-trained ResNet50 model as the base model for feature extraction.
Additional layers are added on top of the base model for classification.
The model is compiled with appropriate loss function, optimizer, and evaluation metrics.</p>

#### Model Training:
<p align="justify"> The model is trained on the augmented training dataset.
Training progress is monitored, and the model's performance is evaluated on the validation set. </p>

#### Model Evaluation:
<p align="justify">Training and validation accuracy and loss curves are plotted to assess the model's performance over epochs.
The distribution of maximum prediction probabilities is visualized to understand the model's confidence in its predictions.
A bar plot of top misclassifications is generated to identify common errors made by the model. </p>

#### Model Saving:
Once training is complete, the trained model is saved for future use.
The saved model is zipped for easy distribution and deployment.
</p>

#### Performance Metrics (Epoch 15)
<b>Training Loss: 9.3738e-04 <br>
Training Accuracy: 99.98%<br>
Validation Loss: 0.4779<br>
Validation Accuracy: 92.24%<br>
Top-5 Accuracy: 97.08%<br> </b>
