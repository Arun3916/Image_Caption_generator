# Image_Caption_generator

In this project, I have explained on how to develop a image caption generator using flickr dataset in python. The project uses keras & tensorflow framework for the implementation. It uses both image features and text features in the project for building the model. This will give a better understanding of how we can leverage the model architecture of different domains for a specific application.

The objective of the project is to predict the captions for the input image. The dataset consists of 8k images and 5 captions for each image. The features are extracted from both the image and the text captions for input. The features will be concatenated to predict the next word of the caption. CNN is used for image and LSTM is used for text. BLEU Score is used as a metric to evaluate the performance of the trained model.

Libraries
-----------
.numpy
.matplotlib
.keras
.tensorflow
.nltk

Neural Network
----------------
VGG16 Network
CNN-LSTM Network
