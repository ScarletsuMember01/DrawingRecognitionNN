# DrawingRecognitionNN

Machine Learning Project using Supervised Learning Algorithm
It can recognize drawing drawn by hand (mouse) !

# Prerequisite

I am using Visual Studio 2022 & the project is created using CLR
So make sure to use it (or otherwise i don't know if it will work)
The project is not using any library or import so nothing else to do

# How to use

First, you need to give some drawing. The drawing will be converted to an array of 0 & 1 and given as an input to the Neural Network.
The best would be to give it 2 or 3 time the same drawing. Make sure that the name you give match the drawin !
Then you can add as much drawing as you want*.
When you are done, click on the train.

Be aware that the more drawing you give, the longer the training will be.

When the training is done, you can check the result!

(*) It's possible that it doesn't work if you give too much different drawing. In that case, try to play with the "epoch" or "hidden size" variable.
More epoch or hidden size will make it more accurate when given more drawing, but training time will also be much longer

# Save your model

You can save your model for later ! (useful when your training takes hours)
