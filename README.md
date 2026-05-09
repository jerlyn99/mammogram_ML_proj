This project utilises TOMPEI-CMMD data from TCIA to explore binary and multiclass classification of mammogram imaging data to benign / malignant and benign / malignant / normal respectively. 

For benign and malignant abnormalities, ROI/segmentation masks were provided. These masks were used to determine the centroid of ROI and 512x512 pixels were cropped from the image.

For normal images with no abnormalities, the ROI crop was done using random 512x512 pixels within the breast tissue of each image.

Based on these ROI images, 3 main models were used to evaluate performance of classifying normal dense breast tissue, benign abnormality and malignant abnormality.

Models explored include below, with Logistic Regression used as a benchmark model
1. Convolutional Neural Network
2. Pre-trained ResNet18
3. Multi-Modal Model
