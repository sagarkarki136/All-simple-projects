

# Brief of the projects:
  

  
## 1.Zindi Flood prediction:
  - This project is about predicting the  flood extent caused by storms in southern Malawi  using the data from Zindi competition
  - Methods used : K fold, Stacking, Out of fold prediction
 
  - Models: XGBoost, GradientBoost,AdaBoost , Bagging , Randon forest
 
  - Result: This was my first attemt at the competition(Zindi flood prediction) and I got on the leader board at rank of 245 of 1100(as of april 2020).RMSE=0.37
 


## 2.American sign language Classification:
 - This project aims at easing the life of blind people by clssifying the letters from hand guestures .The models in the projets are trained on ASL data from Kaggle.
 - Dependencies:  Python 3.6.9 , PIL, Numpy,Matplotlib, Pandas , Pytorch

 - Model: Efficient Net B2(large scope to experiment with better data and other SOTA models and ensembling)

 - Result: The data used is from kaggle ASL and I got 100% accuracy.This was partly because of less images in test data set. For future experiment I will go for better data set along with data augmentation and then have an ensemble of the SOTA models for purpose of deployment

## 3.Mask or non mask classification:
 - The project aims at identifying whether the person is wearing mask or not.This could be deployed during the current pandemic for greater good

 - Dependencies: Python 3.6.9,Numpy,Matplotlib, Tensorflow, Keras

 - Model: InceptionResnetV2

 - Result : It gives 100% accuracy on the test set and vaidation set. Further seting this up with a face detector we can use this for real time detection . This can be done even now with opencv's or any other deep learning package's free face detection software or build your own detector with the help of my face detector notebooks clubbed with mask and non mask classifier model.

## 4.Gun detection:
  - This project is built to increase the security . The project aims at detecting guns from the image or video and this can further clubbed with alarm system or other security measures
 - Tech: Darknet


 - Model: YOLOv3 

 - Result: This mode has been trained for 4000 steps and performs preety well. This can be enhanced with more number of training steps and trying out combinations of the batch size and steps . And of course YOLOv4 is out so .....:)try it

## 5.Emotion Recognition:
 - This project is built for recognising the emotion through image or videos. The models in this project are trained on FER2013 data set. 

 - Dependencies :Python 3.6.9,Numpy,Matplotlib ,Tensorflow, Keras

 - Models tried: InceptionResNet, ResNet

 - Results and further scope: The results rae not that facinating ,58% on test, the data set used is from FER2013 and I suppose it will definetly perform very well once I have more data and better augmentations implemented along with obviously Ensemble and hyper parameter tuning of the models(I am thinking of efficient nets:) ) 
 
 
 ## 6.Face Detection:
  - This project aims at detecting faces from images and videos.The models in this project have been trained on Wider Face dataset. 
  - Tech : Darknet
  - Model: YOLOv3
  - Results: The model has ben trained for only 3000 steps with batch size of 64 over roughly 12100 images from wider face dataset and performs pretty well for such less amount of training steps .A demo prediction is abailable in the output of last cell of the Face_detection.ipynb of the folder. The model can be improved to great extent once we increase the max_batch and steps parameter in config file 
  
 ## 7. Social Distancing Detection:
  - This projects aims at easing the work of survelience for Social distancing  and detecting count of people in region along with violation count.
  
  - Tech: Darknet,OpenCV
   - Model:YOLOv3
   - Results: The model uses the YOLOv3 model in OpenCV to analyze video footage and generate inference.With strong GPU and intrensic and extrensic caliberation of camera we can increase the accuracy and performance of the system and make it deployment ready.
   
 ## 8.Pneumonia Classification:
  - This project aims at identifying Pneumonia cases from xray images .The covid -19 makes the risk of Pneumonia increase substancially and thus deep lerning modls will help the society 
  - Tech: Tensorflow ,sklearn, TPU
  - Model: EfficientNet
  - Results: with unique additions to the fully connected layers the accuracy of the m. The model performs better on the validation set than on the test data.Therefore with more data better ensembling with Densenet varients can improve the performance further  
  
 All the experiments of the projects are done on colab notebook for sole reason of free GPU. So if you wish to build your own model ,you can just clone the git and get the ipynb and run them on colab  and make changes according to your need . I intend to keep improving the model and up to date with current SOTA modeles. So if you want the trained model you can contact me at **sagarkarki136@gmail.com**  
