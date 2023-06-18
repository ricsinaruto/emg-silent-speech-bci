# emg-silent-speech-bci
A proof-of-concept real-time silent speech BCI using EMG electrdes

![Animation](https://github.com/ricsinaruto/emg-silent-speech-bci/blob/main/emg_clip.gif)

This interfaces with the Curry software to get real-time data from EEG/EMG electrodes. Based on triggers a simple decoding model is trained on baseline data and then applied in real-time to decode silent speech. Currently limited to 5 words.

This is a proof-of-concept and there are many other EMG-based silent speech approaches that work much better.
