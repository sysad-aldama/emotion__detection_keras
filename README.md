# Latest changes.

**Added realtime_emotion_plotting.py.** Everything that multi_label_probability.py does PLUS realtime plotting (with legend)
of all emotions over time (t) in seconds and each emotion is plotted with its float(int) values (emotion_angry,emotion_happy, etc...) 

**Added multi_label_probability_test.py.** Shows all emotions and their probabilities. Primary, secondary, inverse emotions [Main emotion detected, secondary emotion is not really working like i want. It is supposed to show a second emotion (2nd probable emotion supposed to be showing. I owuld like to only detect ONE face but haven't had time to work on that. Same accuracy as test.py

## emotion__detection_keras.

Very accurate emotion detection application
requirements: Keras, Tensorflow, pillow, numpy, cv2, time, os, sys
dataset fer2013 (modified)
takes a long time to train epochs.
I recommend using my Emotion_little_vgg.h5. 
the model code is 'little_vgg.py' you can mess with it if you want.
if you do not know what you are doing with the neural networks 
leave dont waste time trying to break something that works perfectly!

just run the test.py or run_detector.py

the fer2013 dataset is modified. i am only using 5 emotions

there is a train, validation folders, out folder too (not really used)

make sure you use absolute paths. no ~ in unix/linux 

everything should work out of the box.

this is specifically made for a friend and hope this can help many people
learn how to work with less. 

dont overdo the models (overfitting) 

do not do more than 25 epochs
its super slow on my 2011 macbook pro 8gb i5 2.2ghz intel graphics
there is no support for this. If you are a student. i will help if you email me. 

email me sysad.aldama@gmail.com quaxiscorp@gmail.com jp.apt3c@gmail.com jp.synergyit@gmail.com

This was inspired by various youtube videos. 
Accuracy is low on most examples
the better the lighting in the webcam or source video the better.

I plan on adding microsoft fer2013plus to play with multilabel emotion detection 
remember LESSISMORE

Thanks 
-JP Aldama 
Quaxis Corporation for Research & Innovation

Stay Indoors and safe from COVID19 (Sars NCov 2)
God bless you all
