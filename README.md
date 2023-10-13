# Audio Processing Feature Extraction

## Overview

This project provides code snippets for audio processing and feature extraction using the Librosa library in Python. Librosa is a powerful tool for music and audio analysis, offering functionalities for loading audio files, visualizing waveforms, creating spectrograms, and extracting features like spectral centroid and MFCCs.

## Credits
- Code snippets and inspiration from:
  - [Towards Data Science: Extract Features of Music](https://towardsdatascience.com/extract-features-of-music-75a3f9bc265d)
  - [Kaggle Notebook: Feature Extraction from Audio](https://www.kaggle.com/code/ashishpatel26/feature-extraction-from-audio/notebook)
- [extras/test-gb.mav (excerpt from the track "Gentle Blade" from the Sekiro: Shadows Die Twice Original Soundtrack - Yuka Kitamura)](https://www.youtube.com/watch?v=tOzQ_OqnY2s)
- [ChatGPT](https://chat.openai.com)

## How it Works

The code snippets cover the following aspects:

1. **Loading and Playing Audio**
   - Load an audio file.
   - Play the audio within a Jupyter Notebook.

2. **Waveform Visualization**
   - Visualize the audio waveform, showcasing its amplitude and structure.

3. **Spectrogram Visualization**
   - Generate and display a spectrogram.
   - Visualize the log-scaled spectrogram for detailed frequency content.

4. **Creating a Sine Wave**
   - Generate a synthetic sine wave signal for testing purposes.

5. **Feature Extraction**
   - Display the waveform of an audio signal.
   - Explore feature extraction techniques.

6. **Spectral Centroid Visualization**
   - Compute and visualize the spectral centroid, representing the center of mass of frequencies in the sound.

7. **MFCC (Mel-Frequency Cepstral Coefficients) Visualization**
   - Compute and display MFCCs, a representation of the short-term power spectrum of a sound.

## Packages Used

- `librosa`: Core library for audio processing.
- `numpy`: Used for numerical operations.
- `matplotlib`: Required for generating visualizations.
- `sklearn`: Used for normalization in some visualizations.

## Setup

Make sure to install the required packages using the following:

```bash
pip install librosa numpy matplotlib scikit-learn
