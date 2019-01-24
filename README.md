
# Plant ID || Plant Classification App

![alt tag](https://github.com/nindyahapsari/plants-id/blob/master/tf_plant_android_2.png)


# Type Of Application

Android

# Installing 

Android Studio

Tensorflow

# About the App

The App that function like a scanner and classify difference of plants by using the mobile’s phone camera. It implement the Deep Learning and Machine Learning technique to make the app understand the difference between plants by showing the percentage of the probability. The percentage of the probability is show in the bottom of the mobile phone screen. 

The Convolutional Neural Network (CNN) model, Cross-Entropy (to minimize the Loss) are use to train the data. The Dataset are full with different type of plants that have around 150 - 200 images of dataset for each plant. 

After training the dataset, i test the classifier with a file, fill with different set of images that are not use in the training session, to see the result of the probability.

And after the testing is done, i convert the original format file into the format that support the mobile framework (Here im implementing in android). 



Framework : Tensorflow, Tensorflow Lite 

Data source: Kaggle



Although the phone’s camera is broken, the app can still come up with good prediction. 





Plants that are recognised and trained so far :

asparagus (Deutsch : Spargel)

chickweed (Deutsch : Gewöhnliche Vogelmiere )

common sow thistle (Deutsch : Gemüse-Gänsedistel)

creeping charlie (Deutsch : Gundermann)

curly dock (Deutsch : Krauser Ampfer)

daisy fleabane (Deutsch : Feinstrahl )

dandellion (Deutsch : Löwenzahn (Taraxacum))

elderberry (Deutsch : Holunder )

field pennycress (Deutsch : Acker-Hellerkraut)

garlic mustard (Deutsch : Knoblauchsrauke)

henbit (Deutsch : Stängelumfassende Taubnessel )

lambs quarters (Deutsch : Weißer Gänsefuß)

peppergrass (Deutsch : Virginische Kresse )

purple deadnettle (Deutsch : Purpurrote Taubnessel )

shepherds purse (Deutsch : Gewöhnliches Hirtentäschel)

sunflower (Deutsch : Sonnenblumen )

toothwort (Deutsch : Gewöhnliche Schuppenwurz)

wild grape vine (Deutsch : Weinrebe )

wild leek (Deutsch : Nordamerikanischer Ramp-Lauch )



# Note

The code is used for android app are from google




# Overview

This repo contains code for the "TensorFlow for poets 2" series of codelabs.

There are multiple versions of this codelab depending on which version 
of the tensorflow libraries you plan on using:

* For [TensorFlow Lite](https://www.tensorflow.org/mobile/tflite/) the new, ground up rewrite targeted at mobile devices
  use [this version of the codelab](https://codelabs.developers.google.com/codelabs/tensorflow-for-poets-2-tflite) 
* For the more mature [TensorFlow Mobile](https://www.tensorflow.org/mobile/mobile_intro) use 
  [this version of the codealab](https://codelabs.developers.google.com/codelabs/tensorflow-for-poets-2).


This repo contains simplified and trimmed down version of tensorflow's example image classification apps.

* The TensorFlow Lite version, in `android/tflite`, comes from [tensorflow/contrib/lite/](https://github.com/tensorflow/tensorflow/tree/master/tensorflow/contrib/lite).
* The Tensorflow Mobile version, in `android/tfmobile`, comes from [tensorflow/examples/android/](https://github.com/tensorflow/tensorflow/tree/master/tensorflow/examples/android).

The `scripts` directory contains helpers for the codelab. Some of these come from the main TensorFlow repository, and are included here so you can use them without also downloading the main TensorFlow repo (they are not part of the TensorFlow `pip` installation).

