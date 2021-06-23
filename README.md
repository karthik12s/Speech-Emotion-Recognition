# Speech Emotion Recognition
Emotion recognition is about identifying and classifying human emotions based on inputs like video, image, voice, text. Speech is one modality of recognizing emotion, with simple modalities and functionality when compared to other inputs.  It enables and simplifies the interaction between human and machine. Recent works have made significant progress in sentimental analysis using Deep Neural Networks (DNN).

Convolution Neural networks made it easy to work on speech emotion recognition, but the main problem with CNN is, it cannot obtain rotational equivariance and spatial coherence between features in MFCCs. As an alternative Capsule Net architecture is implemented, which provides spatial relationship and dynamic routing among speech features. 

## Datasets Worked

### 1.[RAVDESS](https://www.kaggle.com/uwrfkaggler/ravdess-emotional-speech-audio)

Ryerson Audio-Visual Database of Emotional Speech and Song generally termed as RAVDESS database comprises 1440 audio files given by 24 actors in the North American accent.  This database includes calm, happy, sad, angry, fearful, surprise, neutral, and disgust emotions.
### 2.[SAVEE](https://www.kaggle.com/barelydedicated/savee-database)
The SAVEE database comprises audio files recorded in native English. It includes 480 audio samples given by 4 speakers. This database includes anger, sadness, happy, fear, disgust, surprise, and neutral emotions.
### 3.[CREMA D](https://www.kaggle.com/ejlok1/cremad)
CREMA-D is also one such popular database given by 91 actors and comprises 7,442 samples. It includes Anger, Disgust, Fear, Happy, Neutral, and Sad emotions.
### 4.[EMODB](https://www.kaggle.com/piyushagni5/berlin-database-of-emotional-speech-emodb)
The EMODB was developed by the Institute of Communication Science, Technical University portraying Anger, anger, boredom, anxiety, happiness, sadness, disgust and neutral emotions in German Language. It consists of 535 audio files.
### 5.[IEMOCAP](https://www.kaggle.com/samuelsamsudinng/iemocap-emotion-speech-database)
The Interactive Emotional Dyadic Motion Capture (IEMOCAP) database is an acted, multimodal and multi speaker database, recently collected at SAIL lab at USC. It comprises of 2279 audio samples recorded in English language. The emotions included in the database are Anger, Happy, Sad, and Neutral.



|S.NO	|Data Set|Language|Speakers|Emotions|Training Samples|Testing Samples	|Total|
| ------------- | ------------- |------------- | ------------- |--------------------- | ------------- |------------- | ------------- |
|1|RAVDESS|North American English|24 (12 Male, 12 Female)|8 - (Neutral, Calm, Happy, Sad, Angry, Fearful, Disgust, Surprised)|11200|2800|14000|
|2|IEMOCAP|English|10 (5 Male, 5 Female)|4 - (Anger, Happy, Sad, Neutral)|12762|3191|15953|
|3|CREMA-D|British English|91 (48 Male, 43 Female)|6 - (Anger, Disgust, Fear, Happy, Neutral, Sad) |41675|10419|52094|
|4|SAVEE|English|4 (Male)|7 - (Neutral, Happy, Sad, Angry, Fearful, Disgust, Surprise)|2688|672|3360|
|5|BERLIN|German|10 (5 Male, 5 Female)|7 - (Anger, Boredom, Anxiety, Happy, Sad, Disgust, Neutral)|2996|749|3745|
## Model Architecture
![Capsule Net Image](https://firebasestorage.googleapis.com/v0/b/brave-theater-255512.appspot.com/o/Capsulenet.jpg?alt=media&token=4ad680d7-d82b-465f-8a6f-aa14911d1bc8)
# Results
|Dataset Used|Train Accuracy	|Test Accuracy|
|:----------:|:----------:|:---------:|
|EMODB	|99.97%	|97.06%|
|RAVDESS|99.40%	|93.94%|
|SAVEE	|99.83%	|93.60%|
|CREMA D|99.12%	|83.56%|
|IEMOCAP|99.82%	|94.01%|

# References
[CapsNet-Keras](https://github.com/XifengGuo/CapsNet-Keras)
For the detailed Capusle Net Architecture
