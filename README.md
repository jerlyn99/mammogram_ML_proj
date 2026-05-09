This project utilises TOMPEI-CMMD data from TCIA to explore binary and multiclass classification of mammogram imaging data to benign / malignant and benign / malignant / normal respectively. 

For benign and malignant abnormalities, ROI/segmentation masks were provided. These masks were used to determine the centroid of ROI and 512x512 pixels were cropped from the image.

For normal images with no abnormalities, the ROI crop was done using a random 512x512 pixels within the breast tissue.

Based on these ROI images, the goal is to use convolutional neural networks and adapt other pretrained models such as ResNet18 to perform accurate classification of benign / malignant abnormalities as well as differentiate normal dense breast tissue from abnormalities.
