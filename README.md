Training CNN Model

  1) Import the necessary libraries
  2) Import the dataset from the system (training and validation dataset)
  3) Necessary Data Augmentation is applied on the images 
  4) CNN model is applied by adding the Cov2D, Activation, MaxPooling2D, Flatten and Dense using 3 Relu and 1 Sigmoid Activation Layer
  5) Print the model summary
  6) We compile the model Binary_Crossentropy as loss and Adam Optimizer and the metrics being Accuracy
  7) Fitting of the model is done with parameters such as Epochs, Batch size, Training data, etc.
  8) The training and validation accuracy is plotted on a line graph with comparision of the training and validation loss plotted on a different graph

Testing CNN Model
  
   1) Import the necessary libraries
   2) Load the model using a .h5 file name
   3) Import the image from the PC 
   4) The model prdicts the whether the eye has cataract or not
