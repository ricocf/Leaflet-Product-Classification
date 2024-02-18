The dataset consists of 41.6 thousand product images classified into 832 classes. These images were gathered from advertising leaflets spanning several years from various European retailers.
Text information for these images was annotated using Tesseract Open Source OCR, with text extraction conducted under different Page Segmentation Modes (PSM) and using different patterns.

## OCR Image Processing with Tesseract
This Jupyter notebook, OCR_text_extraction.ipynb, showcases Optical Character Recognition (OCR) image processing using the Tesseract library. Its purpose is to extract text from images under various configurations (PSM modes) and save the results in a CSV file.

### Requirements
- Python 3.x
- Tesseract OCR
- pytesseract
- OpenCV
- tqdm
- Pillow

Ensure Tesseract OCR and its corresponding language data are installed on your system.

### Usage
Notebook: <a target="_blank" href="https://colab.research.google.com/github/ricocf/Leaflet-Product-Classification/blob/main/text_model/OCR_text_extraction.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>
1. Follow on-screen instructions to specify the image directory and configure processing parameters.
2. The script offers options to adjust OCR processing settings like PSM, language, and character blacklist.
3. Execute text extraction for each configuration separately based on requirements.
   
Example: For PSM 12 and RGB with a test folder, modify the Tesseract configuration to PSM 12 and RGB. Adjust the Multithreaded Image Processing and Results section by changing main_folder variable to a different directory.
The script will process images and save results in a CSV file.

## OCR Pattern Matching with Tesseract
This Jupyter notebook, OCR_pattern_extraction.ipynb, illustrates Optical Character Recognition (OCR) image processing with Tesseract library. It's intended to extract text from images under different configurations (PSM modes) using various Regular Expression Patterns and save results in a CSV file.

### Requirements
- Python 3.x
- Tesseract OCR
- pytesseract
- OpenCV
- tqdm
- Pillow

Ensure Tesseract OCR and its corresponding language data are installed on your system.

### Usage
Notebook: <a target="_blank" href="https://colab.research.google.com/github/ricocf/Leaflet-Product-Classification/blob/main/text_model/OCR_pattern_extraction.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>
1. Follow on-screen instructions to specify the image directory and configure processing parameters.
2. The script offers options to adjust OCR processing settings like PSM, language, and character blacklist.
3. Execute text extraction for each configuration separately based on requirements.
   
Example: For PSM 6 and RGB with a test folder, modify the Tesseract configuration to PSM 6 and RGB. Adjust the OCR Processing and Pattern Matching section by changing the base_directory variable to a different directory.
The script will process images and save results in a CSV file.

### Credits
This project is created for the Kaggle competition "Retail Products Classification 2023".
If you find this code helpful, consider giving it a star!

### References
[Tesseract](https://github.com/tesseract-ocr/tesseract)

[Tesseract documentation](https://tesseract-ocr.github.io/)

[Original Dataset](https://zenodo.org/records/7869954#.ZFTN8M7P3tV)


#### Note: The text model requires outputs from both OCR Image Processing with Tesseract and OCR Pattern Matching with Tesseract
