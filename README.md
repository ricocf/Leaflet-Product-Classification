## Leaflet Product Classification

![image](https://github.com/ricocf/Leaflet-Product-Classification/assets/67761683/3bed7e35-0b8d-4598-9d9e-c09297708219)

This Git repository contains the code for the Kaggle competition: [Retail Products Classification 2023.](https://www.kaggle.com/competitions/retail-products-classification-2023)

### Abstract
<p align="justify"> This repository presents a model for fine-grained product recognition, specifically based on leaflet images. The dataset comprises 41.6k manually annotated product images categorized into 832 classes. These images were extracted from advertisement leaflets collected over several years from various European retailers. The project explores three different approaches for fine-grained product classification: Classification by Image, by Text, and by Image and Text. The "Classification by Text" approach utilizes text extracted directly from the leaflet product images. The study demonstrates that combining image and text inputs improves the classification accuracy, particularly for visually challenging products. The final model achieves an impressive accuracy of 97% with a Top-3 score of 99.2%. </p> 

### Repository Contents
<ul>
  <li><a href="https://github.com/ricocf/Leaflet-Product-Classification/blob/main/image_model/train_model.ipynb">image_model/train_model.ipynb:</a> Jupyter notebook containing code for model training.</li>
  <li><a href="https://github.com/ricocf/Leaflet-Product-Classification/blob/main/image_model/test_model.ipynb">image_model/test_model.ipynb:</a> Jupyter notebook for testing the trained model and generating predictions.</li>
  <li><a href="https://github.com/ricocf/Leaflet-Product-Classification/blob/main/text_model/OCR_text_extraction.ipynb">text_model/OCR_text_extraction.ipynb:</a> Jupyter notebook for text extraction using Tesseract.</li>
  <li><a href="text_model/OCR_pattern_extraction.ipynb">text_model/OCR_pattern_extraction.ipynb:</a> Jupyter notebook for text extraction using Tesseract with patterns.</li>
   <li><a href="https://colab.research.google.com/github/ricocf/Leaflet-Product-Classification/blob/main/text_model/text_model.ipynb">text_model/text_model.ipynb:</a> Jupyter notebook to classify OCR (Optical Character Recognition) extracted text data into different product categories.</li>
  <li><a href="https://github.com/ricocf/Leaflet-Product-Classification/tree/main/data/extracted_text_data">/data/extracted_text_data:</a> Extracted text data for different configurations.</li>
</ul>

### Usage
Please review the README files located in the respective directories for information regarding the image and text models.

#### Image Model
[Image Model Guide](https://github.com/ricocf/Leaflet-Product-Classification/blob/main/image_model/README_image_model.md)

Execute train_model.ipynb to train the model. <a target="_blank" href="https://colab.research.google.com/github/ricocf/Leaflet-Product-Classification/blob/main/image_model/train_model.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

Use test_model.ipynb for testing and predicting with the trained model. <a target="_blank" href="https://colab.research.google.com/github/ricocf/Leaflet-Product-Classification/blob/main/image_model/test_model.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

#### Text Model
[OCR Guide](https://github.com/ricocf/Leaflet-Product-Classification/blob/main/text_model/README_OCR.md)

[Text Model Guide](https://github.com/ricocf/Leaflet-Product-Classification/blob/main/text_model/README_text_model.md)

Execute text_model.ipynb to train the model. <a target="_blank" href="https://colab.research.google.com/github/ricocf/Leaflet-Product-Classification/blob/main/text_model/text_model.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

### Credits
This project is created for the Kaggle competition "Retail Products Classification 2023".

If you find this code helpful, consider giving it a star!

### References
[Link to Kaggle competition](https://www.kaggle.com/competitions/retail-products-classification-2023)

[Original Dataset](https://zenodo.org/records/7869954#.ZFTN8M7P3tV)

[Fine-Grained Product Classification on Leaflet Advertisements](https://arxiv.org/abs/2305.03706)
