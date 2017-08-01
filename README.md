# NightChord

### Python-Based music creation software, capable of converting a lyric video on Youtube into a [video like this](https://www.youtube.com/watch?v=ZbNzXQX542c)


I used this project as an introduction to Python Classes and to stregnthen my REGEX skills.

This program can generate Nightcore video by inputting one of the following paramters:

 * Youtube URL
 * Artist / Song Name
 * Locally Saved MP4/AVI
 * Locally Saved MP3

You can also pull song names from Billboard Top-X Charts to use for video generation.

Essentially, this programs automates the process of Downloading/Remixing/Transcribing/Uploading Nightcore videos.  I have automated all of these processes using various techniques.  Everything I'm currently using is more of a proof of concept solution rather than a solution that's set to scale.  For instance, I'm using PyAutoGUI in conjunction with Audacity to remix Mp3 files, this is extremely computationally intensive compared to a CIL like SOX.  Regardless, this program is still under developement and I hope to improve the methods I'm using as the time goes on.

Current Features:

* Create Video with Youtube URL
* Create Video with Youtube Artist / Song
* Create both MP3 and MP4 Files
* Generate Videos from Top-X Billboard Chart Songs
* Recreate Lyric Videos with ~98% Accuracy
* Randomly Choose Background Images from a database of Anime Wallpapers
* Cycle through User-Agents to reduce Requests Limits on Youtube
* Set song speed and pitch change
* Grab words with low OCR Confidence
* Send unknown words to [DeathByCaptcha](http://www.deathbycaptcha.com/) to obtain 100% Accuracy
* Generate Word Coordinates in Lyric Videos
* Calculate Amount of Spaces in a lyric video (To Improve Accuracy of OCR)
* Write OCR results to an image with dynamic font choice

To Do:

* Implement the ability to scan a Spotify Playlist
* Create a GUI for generating videos
* Do everything from CIL tools rather than Audicity
* Add the ability to generate Keywords and Video Descriptions
* Post videos automatically
* Graph the relationship between views and speed variables


