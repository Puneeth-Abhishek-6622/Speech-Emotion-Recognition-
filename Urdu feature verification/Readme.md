# Urdu Speech Emotion Dataset  

This dataset is sourced from the [URDU-Dataset](https://github.com/siddiquelatif/URDU-Dataset/blob/master/README.md), which contains speech recordings in the Urdu language labeled with different emotions. The original dataset consists of multiple audio samples representing various emotions.  

## Data Selection  
For my experiment, I have used **only 175 files** from this dataset. The selection was based on the requirement of my **speech emotion recognition model**, ensuring that the chosen samples align with the emotions my model was trained on. Additionally, since the dataset originally includes the **fear emotion**, which is not present in my training data, I have excluded those samples to maintain consistency in classification.  

## Purpose  
The selected audio files were processed to extract features such as **Zero Crossing Rate (ZCR), Root Mean Square Energy (RMSE), MFCCs, and Mel Spectrograms**, formatted in the same structure as the training data. These features were then used to evaluate my pre-trained speech emotion recognition model’s ability to generalize to Urdu speech data.  
