# Emotion
This software recognizes human faces and their corresponding emotions from a video or webcam feed. Powered by OpenCV and Deep Learning.

![Demo](https://github.com/petercunha/Emotion/blob/master/demo/demo.gif?raw=true)


## Installation

Clone the repository:
```
git clone https://github.com/petercunha/Emotion.git
cd Emotion/
```

Install these dependencies with `pip3 install <module name>`
-	tensorflow
-	numpy
-	scipy
-	opencv-python
-	pillow
-	pandas
-	matplotlib
-	h5py
-	keras

Once the dependencies are installed, you can run the project.
`python3 emotions.py`


## To train new models for emotion classification

- Download the fer2013.tar.gz file from [here](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data)
- Move the downloaded file to the datasets directory inside this repository.
- Untar the file:
`tar -xzf fer2013.tar`
- Download train_emotion_classifier.py from orriaga's repo [here](https://github.com/oarriaga/face_classification/blob/master/src/train_emotion_classifier.py)
- Run the train_emotion_classification.py file:
`python3 train_emotion_classifier.py`


## Deep Learning Model

The model used is from this [research paper](https://github.com/oarriaga/face_classification/blob/master/report.pdf) written by Octavio Arriaga, Paul G. Plöger, and Matias Valdenegro.

![Model](https://i.imgur.com/vr9yDaF.png?1)


## Credit

* Computer vision powered by OpenCV.
* Neural network scaffolding powered by Keras with Tensorflow.
* Convolutional Neural Network (CNN) deep learning architecture is from this [research paper](https://github.com/oarriaga/face_classification/blob/master/report.pdf).
* Pretrained Keras model and much of the OpenCV code provided by GitHub user [oarriaga](https://github.com/oarriaga).

# På svenska
För att använda denna repository behövs följande python moduler
-	tensorflow
-	numpy
-	scipy
-	opencv-python
-	pillow
-	pandas
-	matplotlib
-	h5py
-	keras

Dessa kan installeras med pip genom att man i konsolen skriver
`pip3 install tensorflow numpy scipy	opencv-python	pillow pandas matplotlib h5py keras`

För att köra programmet så exekverar man filen `emotions.py` i mappen `Emotions`. Börja med att navigera till mappen `Emotions` och sedan exekvera följande
`python3 emotions.py`

# Träning på nytt
- För att hämta träningsdata för modellen så finns det i filen fer2013.tar.gz från [here](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data)
- Flytta den nedladdade filen till mappen `Emotions`.
- Kör
`tar -xzf fer2013.tar`
- Ladda ned train_emotion_classifier.py från [here](https://github.com/oarriaga/face_classification/blob/master/src/train_emotion_classifier.py)
- Kör filen train_emotion_classification.py :
`python3 train_emotion_classifier.py`
