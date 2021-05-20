# Devnagri-Handwritten-Recognition
This is the code of Handwritten Hindi Recognition system using Deep Learning and more precisely using Computer Vision.

# SOME IMPORTANT POINT:
It can be noticed that when you open the main file (MOSAIC_try.ipnyb file) it seems there is an error in the code but don't worry about it the code is
fine and it works ..

# THE DATASET:
I used the dataset provided by Kaggle whose link is: https://www.kaggle.com/jhashanku007/devnagri-hindi-dataset        
But feel free to use your dataset...

# HOW TO RUN ON YOUR TRAINING AND TEST SET:
Well, in the code it has provided the option to give the location of folder of your test and training set. By provivng the correct directory it will work..
But the important point is if you have to make it predict on your customise letters, then there are two ways to do so..

1. Include the format of letters on which you are going to predict in the test and train dataset (CLEVER WAY !!)
2. Now, the second is to do some image preprocessing by the use of OTSU Thresholding, noise removal and other similar process.

# THE IMAGE AUGMENTATION PART ..
The image augmentataion of the image worked fine for me under the mentioned arguments values but it may be different for you..So, feel
free to do some experiment.

# THE IMAGE PREPROCESSING PART:
I am adding here the reference for the image preprocessing part. The main notion of this project to create an univerasal recognition system which works for all types of 
Devnagri Letter.
It was actually desingned for Devnagri work recognition but it didn't worked. SO, TAKE IT AS A SURCE OF REFERENCE 
ONLY OR AS A BASE WORK..

ANY MODIFIACTION IN THIS PART IS HIGHLY WELCOMED !!
