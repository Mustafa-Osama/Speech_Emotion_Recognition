
# Speech Emotion Recognition

## Defenition

First, lets define SER i.e. Speech Emotion Recognition.

* Speech Emotion Recognition, abbreviated as SER, is the act of attempting to recognize human emotion and affective states from speech. This is capitalizing on the fact that voice often reflects underlying emotion through tone and pitch. This is also the phenomenon that animals like dogs and horses employ to be able to understand human emotion.

## Reasons for SER

Why we need it?

* Emotion recognition is the part of speech recognition which is gaining more popularity and need for it increases enormously. Although there are methods to recognize emotion using machine learning techniques, this project attempts to use deep learning to recognize the emotions from data.

* SER(Speech Emotion Recognition) is used in call center for classifying calls according to emotions and can be used as the performance parameter for conversational analysis thus identifying the unsatisfied customer, customer satisfaction and so on.. for helping companies improving their services

## Datasets

* RAVDESS
* CREMA
* TESS
* SAVEE

Each dataset contains different number of records with different emotions so i merged them together to increase the number of records for better performance so finally, our new dataset has about 12000 records with 8 emotions which are ("happy", "sad", "angry", "calm", "disgust", "neutral", "surprise", "fear")

## Models

In this repo, I have implemented SER with two different models.

### First model:
    
I have built audio classification model using **LSTM** and feature extraction.

Feature extraction techniques used in this project was :

* ZCR
* Chroma_stft
* MFCC
* Root Mean Square Value
* MelSpectogram

### Second model:

I have built audio classification model using **Conv2D** by converting each record to its **spectrogram** which is a way to represent audio like wave form.