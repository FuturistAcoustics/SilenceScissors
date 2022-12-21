# SilenceScissors
SilenceScissors allows you to remove silence from audio files. Currently, you can set the RMS amplitude threshold, attack time, and release time to remove areas of silence in your audio files. Works great for removing the down-time in a podcast to get just speech and save time.

Output:
https://user-images.githubusercontent.com/118419111/208936087-979fe480-add9-4d94-9904-56c5265ef528.mov

Input:
https://user-images.githubusercontent.com/118419111/208918327-7c39e17f-6be7-4505-8a14-691b1e129f14.mov

# Feature Aims
## High Priority
- Set the threshold in dBFS (not raw RMS)
- Add hold
- Compatibility for both mono and stereo
- Compatibility with different bit depth WAVs
## Mid Priority
- Check functionality at different sampling rates
- Compatible with WAV, AAC, MP3
## Low Priority
- Auto-detects most probable thershold
- Compatible with video (edits the footage)
