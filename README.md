# "Great Job!" End Card
A collection of assets you can use to make a Tim &amp; Eric-skit-style 'Great Job!' end card
## Provided Files
1. GreatJobTextAnimation.mov (RGB+Alpha Channels)
2. camera_shutter.wav
3. GreatJobAudio.wav
## How to make the end card (Premiere Pro)
1. Get your comedy video made and ready, then in Premiere Pro, at the frame where you want the 'camera flash' and freeze frame, click `Clip > Video Options > Add frame hold`
2. Stretch the held frame out for a few seconds
3. In the `Effects` tab, search for `Fast Color Corrector` and drag it onto the held frame
4. In the `Effect Controls` window, look for `Saturation` and turn it down to `0`
5. Now search for the transition called `Dip to White` and drag it between the end of the video and the held frame
6. In a 59 fps (frames-per-second) sequence (the recommended setting) the duration of the transition should be set to `00;00;00;17`
7. Use the razor blade cutting tool to remove any sound after the beginning of the held frame (the middle of the transition)
8. Drag the `camera_shutter.wav` sound effect into the timeline, it should be placed a couple of frames after the beginning of the transition
9. Drag the `GreatJobTextAnimation.mov` animation video into the video layer above the held black-and-white frame
10. With the animation video selected in the timeline, adjust the size and position in the `Effect Controls` window by adjusting the `Position` and/or `Scale` parameters
11. Now drag the audio `GreatJobAudio.wav` into the timeline and line it up with the 'Great Job!' text animation
12. Bob Odenkirk's voice begins the phrase 'Great Job!' when the handwriting animation is between the letters 'O' and 'B'.  Line up the sounds accordingly. (If you listen to the pen scribbling sound closely, you can hear the 'tap-tap' of the exclamation mark being written)
## Tips
* The sequence should be set to either 59 or 60 fps to make the animation look its best
* If your software is lagging during playback after adding the transparent video, decrease the video preview resolution by clicking the little dropdown menu underneath the video preview that says `Full` and change it to `1/2` or `1/4`
* Your video editor must have alpha-channel support to use the animation video provided
* See the screenshot for roughly how the clips will be arranged to make the end card
## End Card Timeline Example
![Screenshot demonstrating final timeline configuration](/GreatJobEndCardTimelineExample.jpg)
