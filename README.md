# Spoken-Language-Identification

This project performs speech recognition to recognize the language of given speech utterance from crowd source files. Librosa packacge in python was used to extract 64 dim MFCCs which were used as features and additional pre-processing for the audio files was done using SoX. GRU (Gated Recurrent Unit) model was implemented to classify the audio into different language such as English, Hindi and Mandarin.
