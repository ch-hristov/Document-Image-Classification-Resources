# Document classification resources 📃

The goal of this repository is to create a library of useful resources that may help researchers in solving the problem of document classification. This document is repeatedly updated.

## State of the art:
The best performing model can be found here: 
https://paperswithcode.com/task/document-classification

## Datasets
The majority of literature uses the Tobacco-3482 and the RVL-CDIP datasets. 

With the help of https://eastai.eu, I can provide the Cyrillic multimodal document set (CMDS). This dataset consists of 3789 pairs of images and text across 31 categories downloaded from the Bulgarian ministry of finance. The text was extracted with Tesseract OCR from the images through the bulgarian language module for OCR of Tesseract 5 (tesseract v5.0.0-alpha.20200328 leptonica-1.78.0). The categories include grids, letters, advertisements and more. For the full list of categories you can download the dataset or send me a request at christo@thracia.app. Please refer to this repository if you decide to use this dataset within your own work. 

Additionally, I provide the Unlabelled Cyrillic Dataset for unsupervised learning. This dataset consists of 567 .pdf documents downloaded from the Ministry of Interior Affairs.

1. Tobacco 3482 - https://www.kaggle.com/patrickaudriaz/tobacco3482jpg
2. RVL-CDIP - http://www.cs.cmu.edu/~aharley/rvl-cdip/
3. CMDS - https://drive.google.com/file/d/1m4MZf9HU4m6h9AFdYNGPbwOwm0bQyztQ/view?usp=sharing
4. UCD - https://drive.google.com/file/d/1VFW89hGEDijDSBjD2AooU0urvjg6iYCv/view?usp=sharing


## Models

### Image models

- EfficientNet - a model that is fit for the document classification problem due to availability of document in mostly high resolution 
 Link: https://arxiv.org/abs/1905.11946

### Text models
OCR text for RVL-CDIP and Tobacco 3482 can be downloaded from.

https://github.com/Quicksign/ocrized-text-dataset/releases

Where RVL-CDIP is QS-OCR-Large.tar.gz and Tobacco 3482 is QS-OCR-small.tar.gz

#### Preprocessing
There are several steps that you may take to preprocess the text after extraction

## Multi modal fusion research

- Survey of multimodal fusion methods* - This survey does an excellent job at explaining the various pros/cons of multimodal fusion approaches https://ieeexplore.ieee.org/document/8715409.

*You may need a subscription to access this paper
