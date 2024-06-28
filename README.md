# Text-Document-Orientation-Detection

This is implementation of the paper "Text Document Orientation Detection Using CNN". The paper can be found [here](https://www.researchgate.net/publication/351726231_Text_Document_Orientation_Detection_Using_Convolutional_Neural_Networks).
The final classification layer has been replaced by the number of classes i.e 8.
## Dataset
Dataset used for training and testing are [Financial Document Image Dataset](https://www.kaggle.com/datasets/mehaksingal/personal-financial-dataset-for-india) and [Personal Identification Image Dataset](https://www.kaggle.com/datasets/mehaksingal/personal-identification-image-dataset-for-india) from kaggle.

## Data Preprocessing
Images are rotated at 45-degree intervals and resized to 400 x 400 pixels.

