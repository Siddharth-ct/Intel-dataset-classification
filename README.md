# Intel-dataset-classification
Classification model for Intel dataset

Link to Kaggle dataset: https://www.kaggle.com/datasets/puneet6060/intel-image-classification?datasetId=111880&sortBy=voteCount


## About the dataset
This is image data of Natural Scenes around the world.

<img src="https://github.com/Siddharth-ct/Intel-dataset-classification/blob/main/sample_data/Screenshot%20from%202022-08-02%2000-22-59.png">

This Data contains around 25k images of size 150x150 distributed under 6 categories.

{'buildings' -> 0,
'forest' -> 1,
'glacier' -> 2,
'mountain' -> 3,
'sea' -> 4,
'street' -> 5 }

The Train, Test and Prediction data is separated in each zip files. There are around 14k images in Train, 3k in Test and 7k in Prediction.

## Example images from the dataset
<img src="https://github.com/Siddharth-ct/Intel-dataset-classification/blob/main/sample_data/111.jpg" width="180px"></img>
<img src="https://github.com/Siddharth-ct/Intel-dataset-classification/blob/main/sample_data/114.jpg" width="180px"></img>
<img src="https://github.com/Siddharth-ct/Intel-dataset-classification/blob/main/sample_data/115.jpg" width="180px"></img>
<img src="https://github.com/Siddharth-ct/Intel-dataset-classification/blob/main/sample_data/136.jpg" width="180px"></img>
<img src="https://github.com/Siddharth-ct/Intel-dataset-classification/blob/main/sample_data/137.jpg" width="180px"></img>
<img src="https://github.com/Siddharth-ct/Intel-dataset-classification/blob/main/sample_data/139.jpg" width="180px"></img>
<img src="https://github.com/Siddharth-ct/Intel-dataset-classification/blob/main/sample_data/142.jpg" width="180px"></img>
<img src="https://github.com/Siddharth-ct/Intel-dataset-classification/blob/main/sample_data/153.jpg" width="180px"></img>
<img src="https://github.com/Siddharth-ct/Intel-dataset-classification/blob/main/sample_data/155.jpg" width="180px"></img>
<img src="https://github.com/Siddharth-ct/Intel-dataset-classification/blob/main/sample_data/165.jpg" width="180px"></img>
<img src="https://github.com/Siddharth-ct/Intel-dataset-classification/blob/main/sample_data/177.jpg" width="180px"></img>
<img src="https://github.com/Siddharth-ct/Intel-dataset-classification/blob/main/sample_data/19.jpg" width="180px"></img>
<img src="https://github.com/Siddharth-ct/Intel-dataset-classification/blob/main/sample_data/24.jpg" width="180px"></img>
<img src="https://github.com/Siddharth-ct/Intel-dataset-classification/blob/main/sample_data/26.jpg" width="180px"></img>
<img src="https://github.com/Siddharth-ct/Intel-dataset-classification/blob/main/sample_data/40.jpg" width="180px"></img>
<img src="https://github.com/Siddharth-ct/Intel-dataset-classification/blob/main/sample_data/43.jpg" width="180px"></img>
<img src="https://github.com/Siddharth-ct/Intel-dataset-classification/blob/main/sample_data/12.jpg" width="180px"></img>

<b> Images with classes </b>
 
 <img src="https://github.com/Siddharth-ct/Intel-dataset-classification/blob/main/sample_data/Screenshot%20from%202022-08-02%2000-23-16.png">


## Implementation accuracy
Without VGG16: Accuracy=0.76
With VGG16: Accuracy=0.86


The accuracy is acceptable for this level of code. VGG 16 parameters can be tweaked to increase accuracy.

## The following additional plots and charts were made to understand the model beter.
<b>Without VGG 16</b>

<img src="https://github.com/Siddharth-ct/Intel-dataset-classification/blob/main/sample_data/Screenshot%20from%202022-08-02%2000-23-34.png">

<b>Confusion Matrix</b>

<img src="https://github.com/Siddharth-ct/Intel-dataset-classification/blob/main/sample_data/Screenshot%20from%202022-08-02%2000-23-46.png">

<b>With VGG 16</b>

<img src="https://github.com/Siddharth-ct/Intel-dataset-classification/blob/main/sample_data/Screenshot%20from%202022-08-02%2000-23-58.png">
