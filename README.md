Paper2Movie
===========
A few months ago, I stumbled upon [a timelapse of a research paper](http://youtu.be/hNENiG7LAnc) by Tim Weninger. 
At the time I just started writing my master thesis and I decided I would make a timelapse from my thesis as well. 
Unfortuantely, Weninger did not release his software, so I took matter into my own hands.

This bash script loops through a git repository to creates all the intermediate versions of the paper from the Latex files.
It then calculates the dimensions of the images in the video.
Next, the images are created from the PDFs using the `montage` tool from ImageMagick.
In the last part of the script, the movie is created using `ffmpeg`.

Requirements
------------
* A Unix-based operating system (tested on Ubuntu 12.10);
* A versioned research paper in Git;
* ImageMagick installed;
* FFMPEG with the libx264 encoder installed (Ubuntu users: [follow this guide](https://ffmpeg.org/trac/ffmpeg/wiki/UbuntuCompilationGuide)).

Usage
-----
1. Open the script file with your favorite text editor.
2. Modify the input parameters.
3. Run the script.
4. Enjoy your movie!

Thanks to
---------
* Tim Weninger, for coming up with the idea for a paper timelapse.
* Andrew Ferguson, for creating a [non-generic svn version](https://github.com/adferguson/paper-movies) of a paper2movie script, on which this script was inspired.
* My thesis supervisors and everybody else that helped me with my thesis.

License
-------
Copyright (c) 2013 Raymond Vermaas, licensed under LGPL(2.1). See LICENSE for more details.

Creator
-------
Raymond Vermaas
mail: info at momentofgeekiness.com
website: www.momentofgeekiness.com
