---
layout: post
title:  "Vocal Timbre"
title-prefix: "Weeks 9–10"
date:   2024-03-12 10:10:11 -0500
---

The study of voice and vocal timbre has flourished immensely in the past couple of years. 

-------

{{site.week9}}

{{site.reading9}}

Discussion leaders: {{site.discussion9}}

{{site.homework9}}

This week we'll start using Sonic Visualiser to help analyze timbre. Brace yourselves—it's a user-unfriendly program. But it's immensely powerful. 

For homework this week, I mostly want you to focus on getting set up with all these tools. Then next week, your homework will ask you to build on this in a more profound way.

* 
* [Reference Guide](https://sonicvisualiser.org/doc/reference/3.3/en/)

### Installation process

Each step is a link to more information. 

1. [Download and install Sonic Visualiser](https://www.sonicvisualiser.org/download.html)
2. [Download PYIN plugin v. 1.2](https://code.soundsoftware.ac.uk/projects/pyin/files)
3. [Download libxtract plugin](https://code.soundsoftware.ac.uk/projects/vamp-libxtract-plugins/files)
4. Download MIR.EDU plugin—files are available on Teams.
5. [Install plugins](https://www.vamp-plugins.org/download.html#install)

### Poke around in Sonic Visualiser

To get a feel for the program, and to make sure you did the above installations correctly:

1. Download the files for Beyoncé's "MOVE" which I put into Teams. There is an original audio track and an isolated vocals track I created with iZotope.
2. Open the isolated vocals track in Sonic Visualiser.
3. Open a spectrogram and configure it:
   1. The default pane that opens is a waveform. To open a spectrogram, press G (or go to Pane > Add Spectrogram). You can close out of the waveform if you like by clicking on the x in the top left of that pane.
   2. Change the following settings in the right-hand sidebar that appears with the spectrogram as follows ([screenshot](../assets/sv-settings.png)):
        * Window: &nbsp;&nbsp;&nbsp;2048&nbsp;&nbsp;&nbsp;50%&nbsp;&nbsp;&nbsp;8x
        * Bins: All Bins&nbsp;&nbsp;&nbsp;Log
        * Other settings can be left unchanged.
4. Add new layers with additional analysis.
   1. Go to **Transform > Analysis by maker > Matthias Mauch > pYIN: smoothed pitch track**; hit "OK" and just use the default settings. If needed, change the color of the plot to something that will stand out against the spectrogram.
   2. Go to **Transform > Analysis by maker > libxtract > A–S > RMS Amplitude**; hit "OK" and just use the default settings. On the bottom-right of the property boxes (the right sidebar), toggle off "Show", so that the RMS amplitude graph is hidden instead of overlaid on the spectrogram.
   3. Go to **Layer > Add new time instants layer**. Use this to add annotations to the spectrogram that orient us within the form, as follows:
      1. Refer to the lyrics (uploaded on Teams). Every four lines or so, there is a double-space between lyrics. This indicates different sections of the song. 
      2. For each new section, add a time instant by using the Draw tool. It may help to zoom in enough so that you can visually see where new sections start.
      3. Once you've entered all the time instants, go to the property boxes (the right sidebar) and right-click on the tab for the Time Instants layer and select **Edit layer data** ([screenshot](../assets/edit-time-instants.png)). In the popup window, replace "New Point" with the first word(s) of the lyrics in that section—enough to distinguish the sections and get you oriented.
5. Finally, go to **File > Export image file**. Enter a filename to upload to your homework folder (as a reminder please begin your filename with `9` (the current week number); after that I don't care what the file name is). After you confirm your file name, another dialog box will appear; select the option to export the whole pane.
6. Upload your PNG file to your `homework submit` folder.



-------

{{site.week10}}

{{site.reading10}}

Discussion leaders: {{site.discussion10}}

{{site.homework10}}