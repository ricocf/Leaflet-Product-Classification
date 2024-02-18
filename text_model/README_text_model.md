## OCR Product Classification

This Jupyter notebook, text_model.ipynb aims to classify OCR (Optical Character Recognition) extracted text data into different product categories using machine learning techniques. The data consists of extracted text from product leaflets, and the goal is to build a model that can automatically classify the products based on their descriptions.

### Workflow:
#### Data Loading and Preparation:
Load the raw data from CSV and Excel files.
Preprocess the data by combining columns and cleaning symbols.
Merge multiple datasets for training and testing.

#### Data Processing for Output:
Further processing of merged datasets for final output.
Cleaning and merging output files.

#### Text Cleaning and Tokenization:
Clean and tokenize text data for further processing.
Remove stopwords, punctuation, and irrelevant symbols.

#### Data Processing and Cleaning Script:
Develop a script for automated data processing and cleaning.
Remove specific words, NaN values, and irrelevant characters.

#### Data Preparation and TF-IDF Vectorization:
Prepare the data for model training.
Use TF-IDF vectorization for text representation.

#### Training the Multinomial Naive Bayes Model:
Train a Multinomial Naive Bayes classifier on the prepared data.
Evaluate the model's accuracy.

#### Saving the Model and TF-IDF Vectors:
Save the trained model and TF-IDF vectors for future use.

### Usage
Notebook: <a target="_blank" href="https://colab.research.google.com/github/ricocf/Leaflet-Product-Classification/blob/main/text_model/text_model.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

Follow on-screen instructions to specify the image directory and configure processing parameters.

