# Sound-Editor
.NET researching application for rendering, recording, playback, analyzing and compression of audio data.

The **Sound Editor** app is intended for users who wants to explore audio signals through visual sound analysis. Also tihs program can be used in the ip-telephony since it allows compress and decompress audio data to G.711 codec. The app works only with .mp3 and .wav files.

Main features:
* you can easily playback, pause and rewind music or speech like in audio player
* you can visualize audio signals in 3 ways:
 * wave viewer
 * spectrum viewer
 * spectrogram viewer
* you can record audio from microphone for further analysis
* you can compress and decompress audio data with G.711 codec.

To switch representation of the spectrum use _Left button click_ and _Right button click_.
To record your own audio file you need to create empty .wav file, select available microphone from the list and select the newly created file.

>Requirements:
>* Windows Vista/7/8/8.1/10
>* .NET Framework 4.5 and higher
>* NAudio.dll library. You need to put it in the same directory as the executable file.


Wave and graphical spectrum visualization:

![alt text](https://github.com/Klym/Sound-Editor/blob/dev/Screenshots/1.jpg "Audio visualizing")

Columnar spectrum visualization:

![alt text](https://github.com/Klym/Sound-Editor/blob/dev/Screenshots/2.PNG "Columnar spectrum")

Spectrogram visualization:

![alt text](https://github.com/Klym/Sound-Editor/blob/dev/Screenshots/3.jpg "Spectrogram")
