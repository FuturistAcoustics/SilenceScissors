# SilenceScissors
## Summary
SilenceScissors allows you to remove silence from audio files. Currently, you can set the RMS amplitude threshold, attack time, and release time to remove areas of silence in your audio files. Works great for removing the down-time in a podcast to get just speech and save time.



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
- [ ] Auto-detects most probable thershold
- [ ] Compatible with video (edits the footage)
