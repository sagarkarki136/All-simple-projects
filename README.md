

# Brief of the projects:
  

  
## 1.Zindi Flood prediction:
  - This project is about predicting the  flood extent caused by storms in southern Malawi  using the data from Zindi competition
  - Methods used : K fold, Stacking, Out of fold prediction
 
  - Models: XGBoost, GradientBoost,AdaBoost , Bagging , Randon forest
 
  - Result: This was my first attemt at the competition(Zindi flood prediction) and I got on the leader board at rank of 245 of 1100(as of april 2020).RMSE=0.37
 


## 2.American sign language Classification:
 - This project aims at easing the life of blind people by clssifying the letters from hand guestures .The models in the projets are trained on ASL data from Kaggle.
 - Modules: Pytorch, PIL, Numpy, Pandas

 - Model: Efficient Net B2(large scope to experiment with better data and other SOTA models and ensembling)

 - Result: The data used is from kaggle ASL and I got 100% accuracy.This was partly because of less images in test data set. For future experiment I will go for better data set along with data augmentation and then have an ensemble of the SOTA models for purpose of deployment

## 3.Mask or non mask classification:
 - The project aims at identifying whether the person is wearing mask or not.This could be deployed during the current pandemic for greater good

 - modules: tensorflow, Keras

 - Model: InceptionResnetV2

 - Result : It gives 100% accuracy on the test set and vaidation set. Further seting this up with a face detector (one of my up coming projects) we can use this for real time detection . This can be done even now with opencv's or any other deep learning package's free face detection software clubbed with my model.

## 4.Gun detection:
  - This project is built to increase the security . The project aims at detecting guns from the image or video and this can further clubbed with alarm system or other security measures
 - Tech: Darknet


 - Model: YOLOv3 

 - Result: This mode has been trained for 4000 steps and performs preety well. This can be enhanced with more number of training steps and trying out combinations of the batch size and steps . And of course YOLOv4 is out so .....:)try it

## 5.Emotion Recognition:
 - This project is built for recognising the emotion through image or videos. The models in this project are trained on FER2013 data set. 

 - Modules : Tensorflow, Keras

 - Models tried: Inception, Resnet

 - Results and further scope: The results rae not that facinating ,58% on test, the data set used is from FER2013 and I suppose it will definetly perform very well once I have more data and better augmentations implemented along with obviously Ensemble and hyper parameter tuning of the models(I am thinking of efficient nets:) ) 
 
