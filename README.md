Speech Emotion Recognition
To run this, you need to:
install the following packages using the Pip installer:

1. librosa
2. soundfile
3. numpy
4. sklearn
5. pyaudio
6. numba
- is already trained, you can use `test.py` to test your voice.

You can:
- Tweak the model parameters ( or the whole model ) in `ser.py`.
- Add more data to `data` folder in condition that the audio samples are converted to 16000Hz sample rate and mono channel, `convert_wavs.py` does that.
- Editing the emotions specified in `utils.py` in `AVAILABLE_EMOTIONS` constant.

When you modified anything, you can run `ser.py` to retrain the model.
