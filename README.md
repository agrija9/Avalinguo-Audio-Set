# Avalinguo-Audio-Dataset: Dataset for Speaker Fluency Level Classification 

[Download](#download) | [A peek inside](#a-peek-inside)

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
The dataset can be downloaded as three separate .zip files corresponding to each fluency class (~150 MB total):

[Download Avalinguo Audio Dataset](https://github.com/agrija9/Avalinguo-Audio-Set/tree/master/meta/tar-high-fluency.tar.gz)

## A peek inside

Waveforms and mel-spectrograms of Avalinguo audio dataset recordings:

![Waveforms and mel-spectrograms of ESC-10 dataset recordings](https://github.com/karoldvl/ESC-10/raw/master/ESC-10.png "Waveforms and mel-spectrograms of ESC-10 dataset recordings")


A paper and a side repository with more detailed description about audio classification will be available in due course.

The audioset is currently growing in size and is being maintained by reserachers from the Intelligent Systems Department at ITESM. If you want to contribute to this project feel free to reach me at apreciado42@uabc.edu.mx.
