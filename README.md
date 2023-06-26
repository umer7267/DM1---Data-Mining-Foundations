# DM1 - Data Mining: Foundations

In this repository, I, and my group member, implemented the basic concepts  of Data Mining on the RAVDESS dataset taught by [Prof. Riccardo Guidotti](https://scholar.google.com/citations?user=KZUaK6YAAAAJ&hl=en&oi=ao) in DM1 - Data Mining: Foundations course at Università di Pisa for the year 2022/23.

## Dataset - RAVDESS

The dataset was created from the RAVDESS dataset ([https://zenodo.org/record/1188976](https://zenodo.org/record/1188976)) extracting basic statistics (mean, std, min, max, etc.) from the original audio data and after transforming it using: zero-crossing rate, Mel-Frequency Cepstral Coefficients, spectral centroid, and the stft chromagram. Features were extracted from the 2452 wav files.

## Features Description

1. modality (audio-only)
2. vocal_channel (speech, song)
3. emotion (neutral, calm, happy, sad, angry, fearful, disgust, surprised)
4. emotional_intensity (normal, strong). NOTE: There is no strong intensity for the 'neutral' emotion
5. statement ("Kids are talking by the door", "Dogs are sitting by the door")
6. repetition (1st repetition, 2nd repetition)
7. actor (01 to 24)
8. sex (M, F)
9. channels (number of channels; 1 for mono, 2 for stereo audio)
10. sample_width (number of bytes per sample; 1 means 8-bit, 2 means 16-bit)
11. frame_rate (frequency of samples used (in Hertz))
12. frame_width (Number of bytes for each frame. One frame contains a sample for each channel.)
13. length_ms (audio file length (in milliseconds))
14. frame_count (the number of frames from the sample)
15. intensity (loudness in dBFS (dB relative to the maximum possible loudness))
16. zero_crossings_sum (sum of the zero-crossing rate)
17. 'mean', 'std', 'min', 'max', 'kur', 'skew' (statistics of the original audio signal)
18. mdcc 'mean', 'std', 'min', 'max' (statistics of the Mel-Frequency Cepstral Coefficients)
19. sc_ 'mean', 'std', 'min', 'max', 'kur', 'skew' (statistics of the spectral centroid)
20. stft_ 'mean', 'std', 'min', 'max', 'kur', 'skew' (statistics of the stft chromagram)

## Learning Outcomes

* Fundamental concepts of data knowledge and discovery.
* Data understanding
* Data preparation
* Clustering
* Classification
* Pattern Mining and Association Rules
* Regression
