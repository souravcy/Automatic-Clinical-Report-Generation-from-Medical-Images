# Automatic Clinical Report Generation from Medical Images

The segmentation notebook contains the code where we have performed image segmentation on the chest xray images that we collected from kaggle having the corresponding masks to find the region of interest.

The classification notebook contains the code where we performed the image classification on three categories- covid19,pneumonia and normal.

The feature extractor notebook contains code where the ViT tranformer is used to extract features from X-Ray images.

The tag_extractor notebook contains the code where we have performed parsing. We had the radiology reports from the IU-xray dataset in xml format having several tags, we parsed them, found the important ones and stored them in a csv file for future use.

Datasets - 
https://drive.google.com/drive/folders/1-DDSWQcAvDPrppwBHmrn-UFPl41lY6wA?usp=sharing
https://drive.google.com/drive/folders/18h2nh3WnSY8yxQVyRpJcsjMGFF61ouoc?usp=sharing
