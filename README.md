# Classification-of-Heart-Sound
Classification of Heart Sounds from the Phonocardiogram
Non-invasive methods are always having more research scope especially in the field of medical diagnosing. ECG is one of the traditional techniques through which heart abnormalities are diagnosed worldwide. Also, many imaging techniques are available to detect heart problems. Even though these technologies are existing, many people across the world not having the habit of undergoing regular heart check-ups. Only when some heart related symptoms are enhanced to higher level, they go to physicians for treatment. Many cases of sudden heart attack without much of any pre-symptoms were reported. Also, the chance for death in first attack is high.  
Technology can play a role in addressing the above problem. The Phonocardiogram (PCG) is the method of retrieving the sound of the heart. This sound can capture through simple stethoscope. In this work, we are proposing an artificial intelligence model which have the potential to detect the heart abnormality from the heart sounds. 
The dataset can be downloaded from https://physionet.org
The data was gathered from two sources: (A) from the public via the iStethoscope Pro iPhone app, and (B) from a clinic trial in hospitals using the digital stethoscope DigiScope. There were two tasks associated with this data:
1. Heart Sound Feature Extraction
The first task is to extract the features from the heart sounds within audio data.
2. Heart Sound Classification
The task is to produce a method that can classify real heart sound into one of four categories (Normal, Murmur, Extra-Heart Sound and Artifact).

This work is proposed to implement this classification task in two methods:
1.	Extracting typical features from the signals and modelling these features through ensemble and boosting Machine Learning algorithms.
2.	Use the deep learning algorithms and let the machine to learn the features by its own and make the classification decision. 
