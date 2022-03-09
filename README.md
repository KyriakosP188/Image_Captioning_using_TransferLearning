# Image_Captioning_using_TransferLearning

Important note:
We will build the project largely based upon tensorflow tutorial https://www.tensorflow.org/tutorials/text/image_captioning which tries to solve the same problem with us. We will do some follow-up optimizations though and try to acquire even better results.

In this project we train nn models in "flickr30k-images-ecemod" image dataset with their captions, in order to predict new text captions from scratch.
We use the upper tensorflow tutorial in which we try to improve using more advance technics such as better preprocessing, beam search, introducing a dropout layer to prevent overfitting and using a better encoder (Xception).
The results were calculated using BLEU score metric.
