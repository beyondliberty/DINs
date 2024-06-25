# DINs

This is the  Diverse Insulator Dataset (DINs).  It is based on publicly available images of insulators. The complete dataset is available at https://drive.google.com/file/d/11VsCn1qJ45ecMvw0lNIF0WL4fo4bn9Zs/view?usp=sharing

## Properties

DINs has 1182 original insulator images containing three insulator types.

![image-20230604113527318](./readme/image-20230604113527318.pn

The 3121 bounding box annotations for object detection, the 1091 masks for instance segmentation, and the defects on insulators are  in the dataset. ***VOC*** meant that it was labeled in PASCAL VOC format while ***Mask*** represented that it only had mask marking information.  ***VOC***  contains defects, and the defects are augmented. We do not make defect masks.


### Compared with other datasets

![image-20230604163627327](./readme/compare.png)

### VOC

 We used ***labelImg***  to label the image with bounding boxes and tested it.

The results of the detection of DID 

![image-20230605113153331](./readme/ob.png)

Visualization based on YOLOv5

![PPPP](./readme/PPPP.png)







![gggg](./readme/gggg.png  )





### Mask

 We used ***Lableme***  to mark the insulator outline and then generated mask images based on it.



![mask333](./readme/mask333.png)



The results of the instance segmentation of DID.

![image-20230605114210006](./readme/seg.png)

 

Visualization based on Mask-RCNN.

![image-20230604181959318](./readme/image-20230604181959318.png)





## Abstract

The insulator anomaly detection based on computer vision is fast, high-precision, standardized, and less expensive than manual detection, especially for massive inspection work. Nevertheless, public datasets are scarce and lack variety hampering research progress. Achieving industrial-grade accuracy in inspection still has a long way to go due to the scarcity of insulator datasets with actual complex scenes. We construct a comprehensive beyond the current insulator dataset – the Diverse Insulator Dataset (DINs). DINs has 1182 original insulator images containing three insulator types, i.e., porcelain, glass, and composite. The 3121 bounding box annotations for object detection, the 1091 masks for instance segmentation, and the defects on insulators are also in the dataset. We show that DINs is much more scale and diversity than the current image datasets. Eventually, we illustrate the usefulness of DINs through applications with 95.05\% mAP of object detection and 95.05\% mAP of instance segmentation. We also discuss the effective augmentation methods for insulators.
