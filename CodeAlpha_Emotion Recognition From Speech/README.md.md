**Emotion Recognition from Speech**

**Overview**



This project implements a Speech Emotion Recognition system using deep learning.

The model predicts human emotions from speech audio files using MFCC features and a Convolutional Neural Network (CNN).



The solution is built to run smoothly on Google Colab and supports both WAV and MP3 audio formats.



This project is completed as part of the **CodeAlpha** Machine Learning Internship (Task 2).



**Features**



• Emotion recognition from speech audio

• Supports WAV and MP3 files

• Uses MFCC for feature extraction

• CNN based deep learning model

• Model loads once and allows multiple audio predictions

• Google Colab compatible and stable



**Emotions Supported**



The model predicts the following emotions:



• Angry

• Calm

• Disgust

• Fearful

• Happy

• Neutral

• Sad

• Surprised



**Dataset**



RAVDESS (Ryerson Audio Visual Database of Emotional Speech and Song)



Each audio file contains encoded emotion information which was mapped during training using:



emotion\_map = {

&nbsp;   "01": "neutral",

&nbsp;   "02": "calm",

&nbsp;   "03": "happy",

&nbsp;   "04": "sad",

&nbsp;   "05": "angry",

&nbsp;   "06": "fearful",

&nbsp;   "07": "disgust",

&nbsp;   "08": "surprised"

}



**Technologies Used**



• Python

• TensorFlow Keras

• Librosa

• NumPy

• Scikit Learn

• Google Colab



**Model Architecture**



* The system uses a CNN model trained on MFCC features extracted from speech audio.
* High level flow:
* Load audio file
* Extract MFCC features
* Pass features to CNN
* Predict emotion class



**How to Run the Project (Google Colab)**

**Step 1: Upload model**



Place the trained model file in Colab workspace:



/content/emotion\_recognition\_model.h5



**Step 2: Run the notebook**



Open Emotion\_Recognition\_from\_Speech.ipynb in Google Colab and run all cells.



**Step 3: Upload audio**



When prompted, upload a WAV or MP3 audio file.



**Step 4: Get prediction**



The predicted emotion will be displayed in the output.



You can upload multiple audio files in one session without reloading the model.



Example Output

Predicted Emotion: happy



**Important Notes**



• Audio length around 3 seconds gives best results

• Clear voice improves accuracy

• Background noise can reduce performance

• Label order is carefully matched with training to avoid mismatch



**Internship Task Alignment**



This project fulfills CodeAlpha Task 2 requirements:



✔ Speech Emotion Recognition

✔ MFCC feature extraction

✔ Deep learning based model

✔ Real world audio testing

✔ Clean and reproducible workflow



**Future Improvements**



• Display confidence percentages

• Show probability for all emotions

• Add web interface using Streamlit

• Support real time microphone input (local setup)



**Author**



Muhammad Sadeem Choudhary

AI and Machine Learning Student

CodeAlpha Machine Learning Intern



**License**



This project is for educational and internship purposes only.

