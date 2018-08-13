# Avalinguo-Audio-Dataset: Dataset for Speaker Fluency Level Classification 

[Download](#download) | [Data exploring](#data-exploring)

The **Avalinguo Audio Dataset** is a labeled collection of 1424 audio recordings of non-native English speaking persons. 

This audio set is suitable for performing speaker fluency level classification. The audio recordings are categorized into 3 fluency classes arranged from low to high level. The audios were recording according to the next requirements:

- Spontaneous (non-scripted) conversations
- Random conversation topics
- Audios recorded with low-to-no background noise

**Audio file details:**
```
- Total 1420 audio files
- 5s non-overlapped segments
- Categorized into three fluency classes: low, intermediate, and high
- ~2 hours of recordings
- 450 audio clips per class (aprox.)
- Sample rates ranging from 22050 Hz to 48000 Hz
- Mono and multi-channel
- MP3 format
```

Fluency levels have been defined as:

- **Low fluency**: Person can understand frequently used expressions and give basic personal information. Person can talk about simple things on familiar topics but still speaks with unnatural pauses.
- **Intermediate fluency**: Person Can deal with common situations, for example, traveling and restaurant ordering. Describes experiences and events and is capable of giving reasons, opinions or plans. Can still make some unnatural pauses.
- **High fluency**: Can speak without unnatural pauses (no hesitation), doesn’t pause long to find expressions. Can use the language in a flexible way for social, academic, and professional purposes.

Clips have been manually gathered from three sources:

- Friends/Family recordings
- Language Center from Tecnológico de Monterrey (ITESM)
- Public Youtube Audios


## Download
The dataset can be downloaded as three separate .tar.gz files corresponding to each fluency class (~150 MB total):

[Download Avalinguo Low Fluency Audios](https://github.com/agrija9/Avalinguo-Audio-Set/tree/master/meta/tar-low-fluency.tar.gz) (22 MB)
[Download Avalinguo Intermediate Fluency Audios](https://github.com/agrija9/Avalinguo-Audio-Set/tree/master/meta/tar-intermediate-fluency.tar.gz) (28 MB)
[Download Avalinguo Low High Audios](https://github.com/agrija9/Avalinguo-Audio-Set/tree/master/meta/tar-high-fluency.tar.gz) (98 MB)

The audios can also be individually downloaded in the **audio files** folder.


## Data exploring

Logarithmic power spectrograms of audio frames from the dataset:

![](https://github.com/agrija9/Avalinguo-Audio-Set/blob/master/fluency-levels.gif)

A useful Python module for doing audio analysis is called Librosa. With this module we can perform feature extraction on the audio clips (MFCCs, ZCR, RMSE, etc) to input the feature vectors into machine learning models and classify them.

Librosa also allows to plot audio spectrograms using its *display.specshow* function. The above three spectrograms correspond to the computed power spectrogram on a logarithmic scale for audios from the three fluency classes.

**Another repository with more detailed description about audio classification implementing ML techniques will be available in due course (it will include a paper).**

## Author

Alan Preciado Grijalva

The audioset is currently being maintained by me. If you want to contribute to this project feel free to reach me at apreciado42@uabc.edu.mx.
