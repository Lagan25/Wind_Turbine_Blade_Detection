# Wind_Turbine_BladeSurfaceDamage_Detection

![turbine](https://user-images.githubusercontent.com/50576454/124484524-21ca4080-ddc9-11eb-848a-158b3589be2e.jpg)

An image recognition model based on a deep learning network is proposed for the automatic extraction
of image features and the accurate and efficient detection of wind turbine blade damage. 
In order to improve the recognition performance of the proposed deep learning model, transfer learning and an ensemble learning classifier are used in a convolutional neural network model.
With the fast improvement of wind electricity technology, in current years, a huge variety of wind generators were hooked up and placed into use. 
Since maximum wind generators are hooked up in complex and vicious environments and undergo the impact of alternating masses for a protracted time, 
wind generators revel in severa faults. Maintenance and restore of those faults growth the operational price of the wind generators and reduce their lifestyles cycle. 

This project proposes the fault detection anomaly and detects the images of the surface blades of the wind Tuebine that are defected or Faulty, and provides a 
accurate value of the fault classes. In this project we use a Multi-Class Classsification of Data set that has 4 subclasses of defects.
Image processing involved specifically with image recognition and image classification has taken a huge stride with the advent of high-performance GPU’s and the increase in the processing speeds of images by the computer systems. n different classes of images has helped in solving issues which can be addressed by huge number of 
annotated datasets in teaching a supervised Convolutional Neural Network (CNN) model to classify the images.

# Training_Models
This project showcases three Training models and it's working. 
The extraction of the defect features in the image is an important step in the analysis of the blade image. When there are many defects and the defects are clear, 
the damage to the blade can be identified more accurately if the color and shape features are selected manually. 
However, some defects of the blades are relatively minor and the intrinsic structure of the blade surface. The Dataset is is preprocessed and applying Image Augmentation
we train these Images on 3 Training Models.  

Image Processing and Playing with Images is done using the Convolutional Neural Networks which is the basic Networking method for Image Analytics. 
![90650dnn2](https://user-images.githubusercontent.com/50576454/124955538-bf757800-e034-11eb-980d-7655b0632ced.jpeg)

This Project is built over this base Network Model over which we have added Training Models. And performed the following Models.

1. Convolutional Neural Networks [CNN ]
2. Region Based - CNN [ R-CNN ]
3. Alexnet - Transfer Learning 

