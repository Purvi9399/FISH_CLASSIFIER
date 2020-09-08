# FISH_CLASSIFIER
A model that uses tensorflow api and classifies fishes as per their types.

STEPS I FOLLOWED:-

1.Took the data set images from google chrome by using the download all images extension.

2.Using Image Data Generator to rescale it.

3.Created the base model using MobileNetV2 model (feature extraction)

4.Compiling and trainig for maximum epochs (accuracy for this model was 93.4%)

5.Converting the model to tflite model

6.Building the Gradle in Android Studio

7.Extracting the apk and running it in phone.
