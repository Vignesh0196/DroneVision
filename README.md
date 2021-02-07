# DroneVision
Detecting and Counting humans in Aerial Image ( Drone Vision )

### Implementation
* Usecase implemented using YOLOv3 ( Real-Time Object Detector )
* YOLOv3 Detects images with a speed of 45 FPS, It works faster when compared with other Real-Time Detectors like R-CNN and Faster R-CNN etc

### Example
[![](https://github.com/Vignesh0196/DroneVision/blob/main/result.png)](https://github.com/Vignesh0196/DroneVision)
* Total Humans: 6

### Boundaries:
 * Model trained on COCO dataset contains 80 classes including humans ( Needed for our usecase)
 * Because of lack of dataset related to our usecase, Custom training is not possible. 
   So, I have decided use pretrained model ( trained on COCO dataset ) to detect humans in the given Image
 * Model couldn't able to detect too small humans present in the image, this could be resolved by using Sliding window as a part of the pipeline
 
### Difficulties:
  * Couldn't able to collect datase to Custom Train the model within this short period of time to complete this Assesment
  
### Improvements:
  * By Implementing Sliding Window would improve detection accuracy even if we are using Pretrained Model.
