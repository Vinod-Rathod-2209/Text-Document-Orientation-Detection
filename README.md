# Text-Document-Orientation-Detection

This is implementation of the paper "Text Document Orientation Detection Using CNN". The paper can be found [here](https://www.researchgate.net/publication/351726231_Text_Document_Orientation_Detection_Using_Convolutional_Neural_Networks).
The final classification layer has been replaced by the number of classes i.e 8.
## Dataset
Dataset used for training and testing are [Financial Document Image Dataset](https://www.kaggle.com/datasets/mehaksingal/personal-financial-dataset-for-india) and [Personal Identification Image Dataset](https://www.kaggle.com/datasets/mehaksingal/personal-identification-image-dataset-for-india) from kaggle.

## Data Preprocessing
Images are rotated at 45-degree intervals and resized to 400 x 400 pixels.

## Some Results
| Batch Size | Lr | Epoch | Precision | Recall | F1-score | Accuracy |
|:----------:|:--:|:-----:|:---------:|:------:|:--------:|:--------:|
| 32 | 0.0001 | 50 | 0.90 |	0.90 | 0.90 |	89.35 |
| 64 | 0.0001 |	50 | 0.91 |	0.91 | 0.91 | 90.2 |
| 32 | 0.00001 | 50 | 0.92 |	0.92 | 0.92 |	91.6 |
| 64 | 0.00001 | 50 | 0.92 |	0.92 | 0.92 |	91.8 |
