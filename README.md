This is a small program to parse the information contained in a M3U playlist file and return it in the form of a list of tracks. 

Tracks are Python classes with the following fields:
length - the length of the track in seconds
title - the title of the track
path - the file path to the music file (this is taken directly from the M3U and may be a relative path)

More info on the M3U file format available here:
http://n4k3d.com/the-m3u-file-format
