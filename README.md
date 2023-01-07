# Profanity Detection
This repository include the dataset, python code, and model that used for profanity detection from image that inputted by the user. The program used tesseract module to extracting the text from image. The "classifier.ipynb" file is for building the .h5 tensorflow model and the "final_ml.ipynb" file is for extracting the text from image and detecting profanity by classify the text into 2 labels which is "contain bad words" or "doesn't contain bad words". The model only recognize language of Bahasa Indonesia.

# Dataset
|File name|Description|
| :---: | :---: |
|bad_sentences.csv|List of sentences labeled as 1 (represent contain bad words) and 0 (represent not contain bad words) in Bahasa Indonesia|
|stopwordbahasa.csv|List of stopword in Bahasa Indonesia|
