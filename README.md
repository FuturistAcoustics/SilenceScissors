# SilenceScissors
SilenceScissors allows you to remove silence from audio files. Currently, you can set the RMS amplitude threshold, attack time, and release time to remove areas of silence in your audio files. Works great for removing the down-time in a podcast to get just speech and save time.

## Example
| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| [Original](https://futuristacoustics.com/wp-content/uploads/2022/12/Moby-Dick-Original.wav)      | [ Output](https://futuristacoustics.com/wp-content/uploads/2022/12/Moby-Dick-Output.wav) | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |


## Feature Aims
### High Priority
- Set the threshold in dBFS (not raw RMS)
- Add hold
- Compatibility for both mono and stereo
- Compatibility with different bit depth WAVs
### Mid Priority
- Check functionality at different sampling rates
- Compatible with WAV, AAC, MP3
### Low Priority
- Auto-detects most probable thershold
- Compatible with video (edits the footage)
