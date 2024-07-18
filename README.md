# Audio Data Analysis Using Deep Learning with Python

Audio data analysis is about analyzing and understanding audio signals captured by digital devices, with numerous applications in the enterprise, healthcare, productivity, and smart cities.

In this repository we have done audio data analysis and extracted necessary features from a sound/audio file. Also build an Artificial Neural Network(**ANN**) and Convolutional Neural Network(**CNN**) for classifying music genre.

![NN](https://github.com/ritik8801/Audio-Data-Analysis-Using-Deep-Learning-with-Python/blob/main/images.jpeg)


Pre requisites:

1. **Librosa**: to analyze audio signals in general but geared more towards music. It includes the nuts and bolts to build a MIR(Music information retrieval) system. 

```pip install librosa```


2. **IPython.display.Audio**: Lets you play audio directly in a jupyter notebook.

## Important termanologies:

### Spectrogram
A spectrogram is a visual way of representing the signal strength, or “loudness”, of a signal over time at various frequencies present in a particular waveform.

### Feature extraction from Audio signal
Every audio signal consists of many features. However, we must extract the characteristics that are relevant to the problem we are trying to solve. The process of extracting features to use them for analysis is called feature extraction. Let us study a few of the features in detail.

The spectral features (frequency-based features), which are obtained by converting the time-based signal into the frequency domain using the Fourier Transform, like:

1. Spectral centroid
2. Spectral Rolloff
3. Spectral Bandwidth
4. Zero-Crossing Rate
5. Mel-Frequency Cepstral Coefficients(MFCCs)
6. Chroma feature

Detailed Analysis can be found [here](https://mixed-echinodon-d75.notion.site/A-brief-introduction-to-audio-data-processing-and-genre-classification-using-Neural-Networks-and-pyt-ab17383a912046948a7a8e380d5c01c4).
