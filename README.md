# mask-detection-yolov3
## Problem and statement :- 
Face Mask Detection System uses existing IP cameras and CCTV cameras combined with Computer Vision to detect people without masks ,with mask and mask present but not covered mouth and nose.
          The Indian Government has regulated massive social and *physical distancing* rule against the spreading of *covid-19* virus. And the most important rule is that every people who are still working and still use public transportation or services are obligated to use Medical Mask or regular mask in any kind.
While physical distancing is the most important thing to prevent picking up the virus, wearing face mask could also limit the transmission via mouth and nose.
Also patient who have the virus are highly required to use the mask everywhere they are.
Medical worker who's handling the patient also are required to do so.
So based on those things, I am creating this project that could be implemented in hospital and other public places where people can be crowded.
Mask are crucial to *minimize the chance of being infected or transmitting the virus*, It is important to detect people who doesn't use it. 


## Project description:-
In this project, I am discussed our three-phase COVID-19 face mask detector using computer vision/deep learning pipeline will be implemented.
        From there,  I am create dataset using browser and labellmg software and drag object location on display .  Finally save annotation file form same path. Using python script to train a face mask detector on our dataset using YOLO.  I  here used cloning the Darknet repository for yolo architecture using !git clone command and cloning the architecture of yolov3 which is used for detection .
          I have trained the model with 3 class of images ‘Mask_found’, ‘Mask_cover_50%’  and ‘Mask_not_found’, Where I run my model in Google Colab till more than 2000 iteration which gives me the Highest Accuracy with lower loss when training with 800 images .
Yolo: The yolov3 (you look only once) is one of the faster algorithms for object detection .It is good choice when there is need for real time object detection without loss of  too much accuracy. Yolov3 work on Darknet-53 . this means 53 layers in its network which are trained on the imagenet. 


## project result

### mask not found
[img1]()

### mask found
[img2]()

### Mask_cover_50%
[img3]()
