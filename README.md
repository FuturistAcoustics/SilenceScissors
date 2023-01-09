# SilenceScissors
<a href="https://colab.research.google.com/github/FuturistAcoustics/SilenceScissors/blob/main/SilenceScissors.ipynb" target="_blank">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>


## Summary
SilenceScissors allows you to remove silence from audio files. Currently, you can set the RMS amplitude threshold, attack time, and release time to remove areas of silence in your audio files. Works great for removing the down-time in a podcast to get just speech and save time.

Contributions to Futurist Acoustics GitHub projects welcome!

## Setup
Currently, it's just a simple notebook project. We plan to make it into a script or GUI Python program in the future.

### Example
| Audio         | Duration      |
| ------------- |:-------------:|
| [Original](https://futuristacoustics.com/wp-content/uploads/2022/12/Moby-Dick-Original.wav) | 60 s |
| [ Output](https://futuristacoustics.com/wp-content/uploads/2022/12/Moby-Dick-Output.wav) | 51 s      |


## Feature Aims
### High Priority
- [x] Add attack
- [x] Add release
- [ ] Add hold
- [ ] Set the threshold in dBFS (not raw RMS)
- [ ] Compatibility for both mono and stereo
- [ ] Compatibility with different bit depth WAVs
### Mid Priority
- [ ] Check functionality at different sampling rates
- [ ] Compatible with WAV, AAC, MP3
### Low Priority
- [ ] Is more than just a notebook
- [ ] Auto-detects most probable threshold for user
- [ ] Compatible with video (edits the footage)


## License
MIT License

Copyright (c) 2022 FuturistAcoustics

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
