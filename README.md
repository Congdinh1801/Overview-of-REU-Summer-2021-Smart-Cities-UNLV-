# <div align="center"> Summary of REU Summer 2021 Smart Cities UNLV </div>
### <div align="center"> Author: Dinh Hoang </div>

## I.	Overview:
  During summer 2021, I was lucky enough to participate in the Research Experiences for Undergraduates (REU) Smart Cities program at University of Nevada Las Vegas (UNLV). My work was to apply computer vision and deep learning to test and find out the best models for environmental perception and pedestrian detection in autonomous vehicles which can be applied in emergency braking system. Advanced safety technology in autonomous vehicles can help reduce pedestrian deaths. Two main computer techniques I used for this task including object detection and panoptic segmentation. The models that I tested in object detection including YOLOv5 and YOLOR; for panoptic segmentation the models I used were EfficientPS, Panoptic DeepLab and Real-Time Panoptic Segmentation from Dense Detections.

  Object detection is a task in computer vision such that each object in an image is detected with a bounding box, its associated class, and a confidence score.

  Panoptic segmentation is a unified task of instance segmentation and semantic segmentation such that all pixels are assigned a class label and all object instances are uniquely segmented.
## II.	Object detection with YOLOv5:
1.	Train on nuImages dataset

2.	Train on FLIR dataset
## III.	Object detection with YOLOR: 
## IV.	Panoptic segmentation:
1.	EfficientPS

2.	Panoptic DeepLab

3.	Real-Time Panoptic Segmentation from Dense Detections:

## V.	Future work
   Apply YOLOv5 in Autoware.Auto to test how accurate the model can detect pedestrians in real-time driving application. Autoware.Auto is a stack open-source software for autonomous driving technology

  Develop my own algorithm based on top of YOLOv5 which will be even faster and more accurate for pedestrian detection as well as other traffic detection
## VI.	Additional notes:
	Link to my poster:  https://github.com/Congdinh1801/Poster_presentation_unlv_REUsummer2021
