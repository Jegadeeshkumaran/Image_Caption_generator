# Image_Caption_generator
Tools Used: Keras, VGG16,LSTM, Activation= "relu, "softmax" Optimization – ADAM, loss="categorical_crossentropy", Python
- Using Vgg16 to extract features from photo.
- Preparing The Text Data-Set from the image description.
- One model is created for feature extractor model
- Creating LSTM Model as sequence model (Embedding).
- Adding the output of aboe models into a decoder model.
- THe decoder will give the generated caption of the image
- The test accuracy is almost 94 and the validation accuracy is almost 90
- The test and validation loss are below 0.5
