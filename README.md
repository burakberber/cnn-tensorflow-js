# cnn-tensorflow-js
CNNs usage with tensorflow.js, an example for handwritten data and recognition by cnn
'categoricalCrossentropy' added for optimizer and loss function







RESULTS : *****

Predicting categories for input data is called a classification task.

Classification tasks require an appropriate data representation for the labels

Common representations of labels include one-hot encoding of categories
Prepare your data:

It is useful to keep some data aside that the model never sees during training that you can use to evaluate the model. This is called the validation set.
Build and run your model:

Convolutional models have been shown to perform well on image tasks.
Classification problems usually use categorical cross entropy for their loss functions.
Monitor training to see whether the loss is going down and accuracy is going up.
Evaluate your model

Decide on some way to evaluate your model once it's trained to see how well it is doing on the initial problem you wanted to solve.
Per class accuracy and confusion matrices can give you a finer breakdown of model performance than just overall accuracy.
