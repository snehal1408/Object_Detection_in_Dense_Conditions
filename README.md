# Object_Detection_in_Dense_Conditions

## References: 
1) https://github.com/hsahib2912/Object-detection-reinforcement-learning
2) https://www.geeksforgeeks.org/python-opencv-cv2-rectangle-method/
3) https://github.com/ultralytics/yolov5
4) https://colab.research.google.com/github/ultralytics/yolov5/blob/master/tutorial.ipynb#scrollTo=7mGmQbAO5pQb
5) https://www.youtube.com/watch?v=2nR2e4J4ZaI&t=1025s
6) https://github.com/ultralytics/yolov5/wiki/Train-Custom-Data
            
In this project, Python>=3.6.0 is required with all requirements.txt installed including PyTorch>=1.7. This project require faster GPU, So Google Colab Pro is used as IDE. 

The SKU110K public dataset is downloaded from https://drive.google.com/file/d/1iq93lCdhaPUN0fWbLieMtzfB1850pKwd/edit

There are 10 colab files(.ipynb files):

## 1) Object_detection_SKU110K.ipynb
This files includes object detection using YOLOv5 on SKU110K dataset with 20 epochs, 640 image size and 16 batch size.

## 2) Object_detection_SKU110K_6799.ipynb
This files includes object detection using YOLOv5 on SKU110K-6799 dataset with (1) 20 epochs, 640 image size and 16 batch size and (2) 50 epochs, 640 image size, and 16 batch size.

## 3) Object_Detection_SKU110K_6799-Good_Images_416.ipynb 
This files includes object detection using YOLOv5 on SKU110K-6799_good_images dataset with (1) 50 epochs, 416 image size, and 16 batch size and (2) 50 epochs, 416 image size, and 64 batch size.

## 4) Object_Detection_SKU110K_6799-Good_Images_640.ipynb
This files includes object detection using YOLOv5 on SKU110K-6799_good_images dataset with (1) 50 epochs, 640 image size, and 16 batch size and (2) 50 epochs, 640 image size, and 64 batch size.

## 5) Object_Detection_SKU110K_6799-Good_Images_1024.ipynb
This files includes object detection using YOLOv5 on SKU110K-6799_good_images dataset with (1) 50 epochs, 1024 image size, and 16 batch size and (2) 50 epochs, 1024 image size, and 64 batch size.

## 6) Object_Detection_SKU110K_6799-Cropped_Images_416.ipynb
This files includes object detection using YOLOv5 on SKU110K-6799_Cropped_images dataset with (1) 50 epochs, 416 image size, and 16 batch size and (2) 50 epochs, 416 image size, and 64 batch size.

## 7) Object_Detection_SKU110K_6799-Cropped_Images_640.ipynb
This files includes object detection using YOLOv5 on SKU110K-6799_Cropped_images dataset with (1) 50 epochs, 640 image size, and 16 batch size and (2) 50 epochs, 640 image size, and 64 batch size.

## 8) Object_Detection_SKU110K_6799-Cropped_Images_1024.ipynb
This files includes object detection using YOLOv5 on SKU110K-6799_Cropped_images dataset with (1) 50 epochs, 1024 image size, and 16 batch size and (2) 50 epochs, 1024 image size, and 64 batch size.

## 9) Reinforcement_learning_good_images_1024_threshold_0.5.ipynb
This file includes coding of reinforcement learning with YOLOv5 at IOU at 0.5.

## 10) Reinforcement_learning_good_images_1024_threshold_0.8.ipynb
This file includes coding of reinforcement learning with YOLOv5 at IOU at 0.8.
