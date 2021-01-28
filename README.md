# Finetunnng an Object-detection-model
Finetuning a pre-trained Mask R-CNN model in the "Penn-Fudan Database for Pedestrain Detection and Segmentation". (https://www.cis.upenn.edu/~jshi/ped_html/)

## Dataset 
The Penn-Fudan Dataset contains 170 images with 345 instances of pedastrains. The images come in pairs; the normal image and the mask equivalent. 

[!Screenshot]()
A new custom Dataset class is created, and the expected out puts include 
a) image: a PIL Image of size (H, W)
b) target: a dict containing the following fields: boxes, labels, image_id, area, iscrowd, etc. 


