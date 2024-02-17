## Leaflet Product Classification

This Git repository contains the code for the Kaggle competition: Retail Products Classification 2023.

### Abstract
<p align="justify"> This repository presents a model for fine-grained product recognition, specifically based on leaflet images. The dataset comprises 41.6k manually annotated product images categorized into 832 classes. These images were extracted from advertisement leaflets collected over several years from various European retailers. The project explores three different approaches for fine-grained product classification: Classification by Image, by Text, and by Image and Text. The "Classification by Text" approach utilizes text extracted directly from the leaflet product images. The study demonstrates that combining image and text inputs improves the classification accuracy, particularly for visually challenging products. The final model achieves an impressive accuracy of 97% with a Top-3 score of 99.2%. </p> 

### Repository Contents
train_model.ipynb: Jupyter notebook containing code for model training.
test_model.ipynb: Jupyter notebook for testing the trained model and generating predictions.

### Usage
Execute train_model.ipynb to train the model.

Use test_model.ipynb for testing and predicting with the trained model.

### Credits
This project is created for the Kaggle competition "Retail Products Classification 2023".
If you find this code helpful, consider giving it a star!

### References
[Link to Kaggle competition](https://www.kaggle.com/competitions/retail-products-classification-2023)

[Original Dataset](https://zenodo.org/records/7869954#.ZFTN8M7P3tV)

[Fine-Grained Product Classification on Leaflet Advertisements](https://arxiv.org/abs/2305.03706)
