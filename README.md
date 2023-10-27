# vocals-seprator
 Vocal Meter is a multimedia application written in python that takes any type of sound file, analyzes it then slices part of this file into frames, represent it into spectrogram.

Applying nonnegative filter to the slice, then combine the original sound to the filtered one. 

Generates soft mask for each of the background and foreground sounds, background contains the music, and the foreground contains the vocal words.
Obtain the foreground and background spectrograms by applying the generated mask.

Normalize the background and foreground signal then converts the background and foreground spectrograms back to a time-domain signals audio files).
