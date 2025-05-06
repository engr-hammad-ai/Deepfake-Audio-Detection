# Deepfake-Audio-Detection
This project focuses on detecting DeepFake (synthetically generated) audio using a Convolutional Neural Network (CNN). Real and fake audio files are first preprocessed into Mel-spectrograms—visual representations of the audio frequencies. 
These spectrograms serve as input to a CNN model trained to classify them as real or fake.
The system includes preprocessing, training with early stopping and model checkpointing, and evaluation using a confusion matrix. 
A Streamlit app allows users to test the model by uploading or recording audio live.
