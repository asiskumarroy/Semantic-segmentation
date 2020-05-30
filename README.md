# Semantic-segmentation
A semantic segmentation model which processes the given x-ray image of the chest into a segmented map where the area occupied by the lungs is particularly segmented.The model uses the popular U-NET architecture to process the input image and has been trained using the tensorflow's keras api where dice-loss is used as the loss function and dice-coefficient as the performance metric.

# About the Dataset:
The dataset provided is actually a part of the original dataset on which the model was trained.The entire dataset is available in kaggle.

# About the example:
The predicted output mask for the given input as a test image is an example of how the model works to segment the lungs area after been trained for 57 epochs with a batch size of 8.Further training wasn't performed as the model had reached its minima for which there wasn't any further improve in its loss.

