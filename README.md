# Car Component Identification 
## Problem Statement
Build a system capable of identifying the components and switches inside a car. The user should be able to take a picture and send it to the server, which in return should provide information about the components and switches detected.

## Approach
To address this problem, I explored various computer vision techniques, including classification and object detection. After careful consideration, I opted for object detection as it allows for the localization and classification of multiple objects within an image.

## Resources Used 
Dataset: We utilized the "A Large-Scale Car Dataset for Fine-Grained Categorization and Verification" by Linjie Yang, Ping Luo, Chen Change Loy, Xiaoou Tang. This dataset provides a comprehensive collection of car images suitable for our task.
Dataset Link: https://mmlab.ie.cuhk.edu.hk/datasets/comp_cars/
Tutorials and References:
  Computer Vision Tutorial: Implementing Mask R-CNN for Image Segmentation[https://www.analyticsvidhya.com/blog/2019/07/computer-vision-implementing-mask-r-cnn-image-segmentation/]
  How to Train an Object Detection Model with Keras[https://machinelearningmastery.com/how-to-train-an-object-detection-model-with-keras/]
  Splash of Color: Instance Segmentation with Mask R-CNN and TensorFlow[https://engineering.matterport.com/splash-of-color-instance-segmentation-with-mask-r-cnn-and-tensorflow-7c761e238b46]
  Inception-V4 and Inception-ResNets[https://www.geeksforgeeks.org/inception-v4-and-inception-resnets/]


  ## Dataset Collection and Annotation
    For gathering data aligned with our problem statement, I scraped videos showcasing the interior of cars. These videos were carefully selected to ensure diversity and coverage of various components and switches commonly found inside cars.

Video1[https://www.youtube.com/watch?v=ywo2osnIKZk&t=446s]
Video2[https://www.youtube.com/watch?v=vitActSp9g4]

## Installing the Detectron2 Framework
  Detectron2 is an open-source object detection and segmentation framework developed by Facebook AI Research. It offers flexibility, ease of use, and focuses on rapid research in the field of computer vision. Detectron2 includes implementations of state-of-the-art algorithms such as Mask R-CNN and RetinaNet.

## Why Detectron2?
  Detectron2 is chosen for its versatility and comprehensive feature set. It provides robust implementations of advanced algorithms, making it suitable for a wide range of computer vision tasks. Additionally, Detectron2 is actively maintained and has a vibrant community, ensuring ongoing support and updates.
  
  

  
