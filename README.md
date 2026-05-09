This project utilises TOMPEI-CMMD data from TCIA to explore binary and multiclass classification of mammogram imaging data to benign / malignant and benign / malignant / normal respectively. 

For benign and malignant abnormalities, ROI/segmentation masks were provided. These masks were used to determine the centroid of ROI and 512x512 pixels were cropped from the image.

For normal images with no abnormalities, the ROI crop was done using a random 512x512 pixels within the breast tissue.

Based on these ROI images, 3 main models were used to evaluate performance of
1. Benign / malignant abnormality classification
2. Normal dense breast tissue / breast tissue with abnormality classification

Models explored include
1. Convolutional Neural Network
2. Pre-trained ResNet18
3. Multi-Modal Model
