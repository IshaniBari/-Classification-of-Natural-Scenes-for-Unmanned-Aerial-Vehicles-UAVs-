# Classification-of-Natural-Scenes-for-Unmanned-Aerial-Vehicles-UAVs

### Task - 
Building a CNN model to predict the natural scenes around the flying object to tune the unmanned aerial systems.

### Dataset Description - 
Used the Intel Image data from kaggle for this project. This Data contains around 25k images of size 150x150 distributed under 6 categories.
{'buildings' -> 0,
'forest' -> 1,
'glacier' -> 2,
'mountain' -> 3,
'sea' -> 4,
'street' -> 5 }<br>
The Train, Test and Prediction data is separated in each zip files. There are around 14k images in Train, 3k in Test and 7k in Prediction.
This data was initially published on https://datahack.analyticsvidhya.com by Intel to host a Image classification Challenge
#### Link to the dataset - https://www.kaggle.com/datasets/puneet6060/intel-image-classification

### Summary – 
As part of the final project of the AI-2 course at Univ.AI, we used data released by Intel Corp. which contained round 14k training images distributed under 6 categories of natural scenes (buildings, forests, glacier, mountain, sea and street) to classify images for UAVs.  We augmented the data and trained 3 CNN models with different architectures on the data to classify natural scenes. After training and prediction, used saliency maps and GradCAM to visualize the predicted images.
