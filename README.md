# <div align="center"> Summary of REU Summer 2021 Smart Cities UNLV </div>
### <div align="center"> Author: Dinh Hoang </div>

## I.	Overview:
  During summer 2021, I was lucky to participate in the Research Experiences for Undergraduates (REU) Smart Cities program at University of Nevada Las Vegas (UNLV). My work was to apply computer vision and deep learning to test and find out the best models for environmental perception and pedestrian detection in autonomous vehicles which can be applied in emergency braking system. Advanced safety technology in autonomous vehicles can help reduce pedestrian deaths. Two main computer techniques I used for this task including object detection and panoptic segmentation. The models that I tested in object detection including YOLOv5 and YOLOR; for panoptic segmentation the models I used were EfficientPS, Panoptic DeepLab and Real-Time Panoptic Segmentation from Dense Detections.

  Object detection is a task in computer vision such that each object in an image is detected with a bounding box, its associated class, and a confidence score.

  Panoptic segmentation is a unified task of instance segmentation and semantic segmentation such that all pixels are assigned a class label and all object instances are uniquely segmented.
## II.	Object detection with YOLOv5:
1. My customized tutorial to train YOLOv5 on FLIR dataset: https://github.com/Congdinh1801/yolov5forFLIRdataset
2. Link to the original YOLOv5 github: https://github.com/ultralytics/yolov5
3. More information about YOLOv5 can be found in this well explaind article: https://blog.roboflow.com/yolov5-improvements-and-evaluation/
4. YOLOv5 tutorial provided by the author on Colab: https://blog.roboflow.com/how-to-train-yolov5-on-a-custom-dataset/
5. A useful Youtube tutorial on "How to Train YOLO v5 on a Custom Dataset" https://www.youtube.com/watch?v=MdF6x6ZmLAY and the corresponding Colab notebook https://colab.research.google.com/drive/1gDZ2xcTOgR39tGGs-EZ6i3RTs16wmzZQ
## III.	Object detection with YOLOR: 
a. Original paper https://arxiv.org/pdf/2105.04206 and author's github https://github.com/WongKinYiu/yolor
## IV.	Panoptic segmentation:
1. EfficientPS: 

* Original paper https://arxiv.org/pdf/2004.02307 and author's GitHub https://github.com/DeepSceneSeg/EfficientPS

* My customized tutorial to train EfficientPS on Cityscapes dataset: https://github.com/Congdinh1801/EfficientPS_Cityscapes

2. Panoptic DeepLab

* Original paper https://arxiv.org/pdf/1911.10194 and author's Github https://github.com/bowenc0221/panoptic-deeplab/blob/master/tools_d2/README.md

3. Real-Time Panoptic Segmentation from Dense Detections:

* Original paper https://arxiv.org/pdf/1912.01202 and author's github https://github.com/TRI-ML/realtime_panoptic

## V. Results and Conclusion: 
* YOLOv5 is the best choice for real time pedestrian detection with high accuracy of >47 mAP and fast inference time of >50 fps
* Panoptic segmentation with EfficientPS and Panoptic DeepLabare are accurate but too slow for real time application with inference time less than 1 fps


## VI. Future work
* Apply YOLOv5 in Autoware.Auto to test how accurate the model can detect pedestrians in real-time driving application. Autoware.Auto is a stack open-source software for autonomous driving technology

* Develop my own algorithm based on top of YOLOv5 which will be even faster and more accurate for pedestrian detection as well as other traffic detection
## VII. Additional notes:

* Link to my poster:  https://github.com/Congdinh1801/Poster_presentation_unlv_REUsummer2021


