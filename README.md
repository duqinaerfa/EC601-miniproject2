# EC601-miniproject2
miniproject2 for EC601 in BU
## Before running program
1.Install skimage, tensorflow, numpy<br>
2.Download pictures from Kaggle
## Introduction
1.Use TensorFlow (or any tool you prefer) to recognize between two classes of objects<br>
2.Design your own model<br>
3.Compare between two different systems<br>
## Steps
### 1.Choose roses and sunflowers to classify(delete other folders of flowers from the downloaded pictures)
### 2.cnn_classify.py
    (1)read and resize pictures
    (2)disrupt order
    (3)divide dataset into train&validation
    (4)Build the CNN by defining an inference function which builds layers
    (5)generate model
    (6)train and validate
### 3.Result of cnn_classify
   train loss: 1276.465061<br>
   train acc: 0.599826<br>
   validation loss: 45.094784<br>
   validation acc: 0.792969<br>
   train loss: 31.485623<br>
   train acc: 0.830729<br>
   validation loss: 12.961484<br>
   validation acc: 0.933594<br>
   train loss: 17.162218<br>
   train acc: 0.888889<br>
   validation loss: 12.942560<br>
   validation acc: 0.925781<br>
   train loss: 11.683712<br>
   train acc: 0.926215<br>
   validation loss: 11.139235<br>
   validation acc: 0.925781<br>
   train loss: 7.675296<br>
   train acc: 0.958333<br>
   validation loss: 9.736868<br>
   validation acc: 0.945312<br>
   train loss: 4.916919<br>
   train acc: 0.981771<br>
   validation loss: 9.768824<br>
   validation acc: 0.925781<br>
   train loss: 3.257563<br>
   train acc: 0.986979<br>
   validation loss: 9.553000<br>
   validation acc: 0.933594<br>
   train loss: 2.098731<br>
   train acc: 0.994792<br>
   validation loss: 10.133725<br>
   validation acc: 0.945312<br>
   train loss: 1.476639<br>
   train acc: 0.994792<br>
   validation loss: 9.257919<br>
   validation acc: 0.949219<br>
   train loss: 0.796560<br>
   train acc: 1.000000<br>
   validation loss: 9.824996<br>
   validation acc: 0.945312<br>
### 4.cnn_classify_test.py
A file which can test the result of cnn_classify
