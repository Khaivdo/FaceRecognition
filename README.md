Face recognition using Computer Vision techniques was first attemped, then I tried with Deep Learning. 


## Computer Vision

Face classifier was trained using Haar Cascade features.

It is then deployed by using OpenCV.

<img src="https://github.com/Khaivdo/FaceRecognition/blob/master/results/3.png" height="256" width="324">

However, when I'm angled away from the camera, it misclasssifies me with others as below

Haar Cascade Classifier

<img src="https://github.com/Khaivdo/FaceRecognition/blob/master/results/2.png" height="256" width="324"> 

Real "Kyrie"

<img src="https://github.com/Khaivdo/FaceRecognition/blob/master/images/Kyrie/3.jpg" height="256" width="324">

## Deep Learning

I downloaded [face_recognition](https://github.com/ageitgey/face_recognition) which used
dlib's state-of-the-art face recognition built with deep learning.

<img src="https://github.com/Khaivdo/FaceRecognition/blob/master/results/1.png" height="256" width="324">

## Comparison
Overall, the Haar Cascade classifier has capability of detecting human faces in realtime, but it does not work well with low resolution images or angled faces.

Deep learning method developed by ageitgey could recognize faces with much higher accuracy in different conditions, but it has a disadvantage of high processing time even though the image size was rescaled to 4 times smaller.
