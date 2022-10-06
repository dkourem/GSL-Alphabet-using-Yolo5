# GSl Alphabet recognition using Yolo5. 
## A step in Increasing Accessability for the Greek Deaf Community with Computer Vision utilizing Yolov5.

Utilizing Yolov5, a custom computer vision model was created on the Greek Sign Language alphabet. The project was promoted on social platforms to diversify the dataset. A total of 481 images were collected using social media forms. Manual labels were created of the original images which were then resized, and organized for preprocessing using roboflow platform. Several carefully selected augmentations were made to the images to compensate for the small dataset count. A total of 5244 images were then used for modeling. 

Trying object detection by using images dataset with  augmentation methodology for yolo object detection algorithm.
- You can download the **final augmented dataset (5244 images)** from my [the google cloud](https://drive.google.com/file/d/1ENvL_MK5s3vByZ3ExYS3vRudJvT_-tva/view?usp=sharing).
- You can download the **original source images** from [the google cloud](https://drive.google.com/file/d/1_seYpj8sQENJGv_aTFqK65XkrMN9g_2o/view?usp=sharing).

## Labeling the images
Manual bounding box labels and augmentation process were completed on the original images using the roboflow labelImg software.
Roboflow augmentation process: [https://docs.roboflow.com/image-transformations/image-augmentation](https://docs.roboflow.com/image-transformations/image-augmentation)

## Model Training
mAP: 95.1%
precision: 60.2%
recall: 96.5%


 ## Video Inference Tests  
You can use your webcam to test the model by using the below cloud roboflow url link: 
[webcam inference roboflow url](https://demo.roboflow.com/gsl-fingerspelling/5?publishable_key=rf_Aq2kd1MKvqCTI0spCCEk)

## About Roboflow
[Roboflow](https://roboflow.ai/)  makes managing, preprocessing, augmenting, and versioning datasets for computer vision seamless.
Developers build computer vision models faster and more accurately with Roboflow.
