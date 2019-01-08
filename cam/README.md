# Class Activation Map
This is the keras implementation of Class Activation Map, see more details about the Class Activation Map in the paper http://cnnlocalization.csail.mit.edu/Zhou_Learning_Deep_Features_CVPR_2016_paper.pdf.  

# Model
The CAM model is fine-tuned by using the keras ResNet50 with 10 epochs, NOTE: I have tried to use simple shallow model deinfed by me, but the activation region in the heatmap is quite small and ugly unlike the map created by the ResNet50. 

# Dataset
The dog and cat dataset comes from the kaggle dataset, see https://www.kaggle.com/tongpython/cat-and-dog. 

# Example
![](https://github.com/BigRiceBall/visualization-dl/blob/master/cam/example.png "cat cam")
