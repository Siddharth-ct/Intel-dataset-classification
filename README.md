# Intel-dataset-classification
Classification model for Intel dataset

Link to Kaggle dataset: https://www.kaggle.com/datasets/puneet6060/intel-image-classification?datasetId=111880&sortBy=voteCount


## About the dataset
This is image data of Natural Scenes around the world.

This Data contains around 25k images of size 150x150 distributed under 6 categories.

{'buildings' -> 0,
'forest' -> 1,
'glacier' -> 2,
'mountain' -> 3,
'sea' -> 4,
'street' -> 5 }

The Train, Test and Prediction data is separated in each zip files. There are around 14k images in Train, 3k in Test and 7k in Prediction.

## Example images from the dataset



## Implementation accuracy
--> Data Augmentation Implemented

<b>Train set accuracy:</b> ~94%<br/>
<b>Validation set accuracy :</b> 93.05%<br/>

The accuracy is quite good. The model was trained for 30 epochs. With a bit of tweaking of models layers, dropouts, increasing the number of filters etc and training the model for 100 epochs or more will result in very high accuracy.

## The following additional plots and charts were made to understand the model beter.
<b>Loss vs Epochs</b>

<img src="https://github.com/Siddharth-ct/Gender-Classification-with-CNN/blob/main/files/Screenshot%20from%202022-06-27%2005-26-31.png">


<b>Binary accuracy vs Epochs</b>

<img src="https://github.com/Siddharth-ct/Gender-Classification-with-CNN/blob/main/files/Screenshot%20from%202022-06-27%2005-26-29.png">
