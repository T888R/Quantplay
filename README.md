# Quantplay
A quantized backing track playback module designed for Orac

Quantplay was born out of a specific problem and that was being able to play backing tracks without drift. Octaloops has a quantized playback function but when playing long files back, they gradually drift out of time. I'm assuming this is due to a rounding error in the playback rate value. I avoided this in Quantplay by using the C&G waveplayer~ object and it is now plays back fine.

Operation is simple. Put your backing tracks in the /media/quantplay and you can select the sample for 4 of the slots. Set your clocks BPM to correspond with the BPM of the backing track and click the low C, C#, D, D# to queue playback and the upper octave to stop. The file will start playing back on the next '1' in the middle of the bottom line.

There is a crackling that happens at the beginning of playback and I unfortunately don't know how to fix it :/

***  ALL FILES IN THE QUANTPLAY FOLDER MUST BE MONO. STEREO FILES PLAYBACK AS NOISE  ***
