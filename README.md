# ImageRecoginition_tensorflowjs

This app build using Flask and tensorflow Js

<b> HOW </b>: 
  
  
  pre_requisite: tensorflow be installed
                 Webcam is needed to capture the custom images
  
  Run app using below command:
  
  1) python app.py
  
  2) Open the app using localhost:5002/
    
  3) Wait until the mobilenet is loaded
  
  4) Bring the images of your choice to the webcam and click on respective class ( A or B or C) for the model to learn.
    50 training images for each class would give better prediction
  
  5) Now for testing, capture the image using webcam and click on Predict, the prediction will be displayed above the image. 
  
 <b> WHAT: </b>
      In this Example, App is being trained using the user defined images and predicting the new images throug webcam.
      
      The image captures is fed through Mobilenet model for the predictions and the output is fed through a KNN classifier 
      to predict one among the three classes
 

