# Heart Desease  Diagnostics using neural network


## Overview

activation function : Sigmoid 

Optimazer  : RMS Optimazer based on gradient decent

number of inputs  :12 wich are the features of the cells  : 
age,sex,cp,trestbps,chol,fbs,restecg,thalach,exang,oldpeak,slope,ca,thal

number of hidden layers : 7 in the best cases 

number of output : 1 because its an binary clasification (Malignant begningn)

##### features : 
Attribute Information: 
> 1. age 
> 2. sex 
> 3. chest pain type (4 values) 
> 4. resting blood pressure 
> 5. serum cholestoral in mg/dl 
> 6. fasting blood sugar > 120 mg/dl
> 7. resting electrocardiographic results (values 0,1,2)
> 8. maximum heart rate achieved 
> 9. exercise induced angina 
> 10. oldpeak = ST depression induced by exercise relative to rest 
> 11. the slope of the peak exercise ST segment 
> 12. number of major vessels (0-3) colored by flourosopy 
> 13. thal: 3 = normal; 6 = fixed defect; 7 = reversable defect
##### lable :
Target 1 or 0  binary classification 
 

##### how  the prediction works ?
So first to to train my model I have too a dataset bunch of examples of persones whather they ill or not and then 
train my model with it after I finished the training you get the Best optimal  parameters  to make the predictions 


## Here are some helpful links:
###### Dataset details to understand how it had been collected 
https://www.kaggle.com/ronitf/heart-disease-uci

## Framework
Tensorflow 

## Usage

Just run ``python3 demo.py`` to see the results:

To visulaze your Graph in tensorboard just run ``tensorboard --logdir=/tmp/mnist_tutorial/``
wich the path depends on what you have set in the code "Logdir"

