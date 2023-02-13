# Skin-cancer-segmentation

 
## Task 1 : Skin lesion classification: 

https://github.com/leahcimali/Skin-cancer-segmentation/blob/main/Skin_lesion_classificatio.ipynb

## Task 2 : Skin lesion segmentation using YOLOv5

https://github.com/leahcimali/Skin-cancer-segmentation/blob/main/Projet_YOLOv5_with_Skin_Cancer.ipynb


## Task 3 : Skin lesion segmentation using MaskRCNN with detectron2

https://github.com/leahcimali/Skin-cancer-segmentation/blob/main/Roboflow_Train_Detectron_2_Instance_Segmentation_Mask_RCNN%20.ipynb

## Extra

The dataset for task 2 and task 3 was manually anotated by using the computer vision platform Roboflow. 
https://universe.roboflow.com/horizon-school-of-digital-technologies/skin-cancer-7hnpa/browse?queryText=&pageSize=50&startingIndex=0&browseQuery=true

## mAP

mAP (mean average precision) is a metric used to evaluate the performance of object detection algorithms in computer vision. There are two commonly used variations of mAP: mAP50 and mAP50-95.

mAP50 refers to the mean average precision computed using the standard IoU (intersection over union) threshold of 50%. In other words, for an object detection algorithm to be considered a "true positive" detection, its predicted bounding box must have an IoU overlap of at least 50% with the ground truth bounding box.

mAP50-95 refers to the mean average precision computed using a more stringent IoU threshold of 95%. This threshold is used to evaluate the performance of object detection algorithms on high quality datasets where the objects are well localized and clearly visible.

In summary, mAP50 and mAP50-95 are both metrics used to evaluate the performance of object detection algorithms, but mAP50-95 is a more stringent metric as it uses a higher IoU threshold.




