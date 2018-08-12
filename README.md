# Avalinguo-Audio-Dataset: Dataset for Speaker Fluency Level Classification 

[Download](#download) | [A peek inside](#a-peek-inside)

The **Avalinguo Audio Dataset** is a labeled audio collection of 1424 audio recordings consisting of 3 fluency classes, average 450 audio clips (segments) per class, total of ca. 2 hours recordings, 5 seconds non-overlapped segments.
The audios have sample rates ranging from 22050 Hz to 48000 Hz, are mono and multi-channel and were converted to MP3 format.

This audio set is suitable for performing speaker fluency level classification.

A paper and a side repository with more detailed description about audio classification will be available in due course.

The Avalinguo audio set is a collection of audio recordings of people whose language fluency ranges from low to high. The audio recordings have the following characteristics:

- Spontaneous (non-scripted) conversations
- Random conversation topics
- Audios recorded with low-to-no background noise

The dataset consists of 3 classes of recordings:
- Low fluency: Person can understand frequently used expressions and give basic personal information. Person can talk about simple things on familiar topics but still speaks with unnatural pauses.
- Intermediate fluency: Person Can deal with common situations, for example, traveling and restaurant ordering. Describes experiences and events and is capable of giving reasons, opinions or plans. Can still make some unnatural pauses.
- High fluency: Can speak without unnatural pauses (no hesitation), doesn’t pause long to find expressions. Can use the language in a flexible way for social, academic, and professional purposes.

Clips have been constructed from public field recordings gathered by the **[Freesound.org project](http://freesound.org/)**. The dataset has been prearranged into 5 folds. Clips stemming from the same original source file are contained in a single fold.

**File naming scheme:**
```
category_id - category_name/fold_number-Freesound_clip_ID-take_letter.ogg
```

**File details:**
```
1420 (5s dura-
tion) non-overlapped audio segments comprising three fluency
classes (low, intermediate and high fluency). This is about 2
hours of recordings. The audios have sample rates ranging from
22050 Hz to 48000 Hz, are mono and multi-channel and were
converted to MP3 format.

5-second-long recordings reconverted to a unified format:
- 44100 Hz,
- single channel (monophonic),
- Vorbis/Ogg compression @ 192 kbit/s. 
```

## Download
The dataset can be downloaded as three separate .zip files corresponding to each fluency classes (~150 MB total):

[Avalinguo Audio Dataset](https://github.com/karoldvl/ESC-10/archive/master.zip)

## A peek inside

Waveforms and mel-spectrograms of Avalinguo audio dataset recordings:

![Waveforms and mel-spectrograms of ESC-10 dataset recordings](https://github.com/karoldvl/ESC-10/raw/master/ESC-10.png "Waveforms and mel-spectrograms of ESC-10 dataset recordings")


If you want to contribute to this project feel free to reach me at agrija@gmail.com
