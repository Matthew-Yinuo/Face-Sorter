#Facial Image Classifacation 

## (A)The ML technology used in this classifier 
    The base of this classifier is the Inception v3 model. Inception is a deep convolutional neural network(CNN), 
    which has been pre-trained using ImageNet's "Large Visual Recognition Challenge" data.
    This needs to be used as my laptop's GPU is nothing short of awful.
    We'll be hoping on the final layer of this CNN to help classify our images. 
    Due to the lack of sample size on the project we must take advantage of transfer learning.

## (B)The modules enclosed in this classifier and their functions
    ###Model: Inception-v3 “Mobilenet Models”
        This model is an open-source project released by Google in summer of last year.
    ###URL: https://ai.googleblog.com/2017/06/mobilenets-open-source-models-for.html
  
## (C) How I tested this classifier to evaluate its recognition rate
    I used Tensorboard to visualize the data and ran multiple training cycles to preview performance.
## (D) The problems suffered in development
    Setting up the enviroment was painful to say the least. After uninstalling and reinstalling python and it's related programs half a dozen times I did a full computer reset to make sure there were no conflicting dependecies. This cost over a day but it worked.

## (E) The task allocation of each member
    There were no other members. Shoutout tomahim for the augmentation track though.
    
## (F) Any bonus features or functionalities included in your recognizer
    There is an augmentation library included to handle small sample sizes.
     
## (G) How I feel about doing this project.
    It was interesting to work around having a small sample size and to deal with not having a worthwhile GPU that could handle this level of work.
