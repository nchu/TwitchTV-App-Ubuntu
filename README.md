TwitchTV-App-Ubuntu
===================

This is a broadcasting app for Ubuntu to make streams on Justin.tv and Twitch.tv


TwitchTV Boardcast App by Memorix Pilgrim  12/02/2013

Thank you for downloading and your interest in my app :)

This app is in an early alpha status !


Setup your system for TwitchTV (Ubuntu or any Ubuntu/Debian based distribution)

NOTE: Xterm Terminal must be installed !

1.Open your terminal:

sudo apt-get install ffmpeg libavcodec-extra-52

if this doesn't work try this:

sudo apt-get install ffmpeg libavcodec-extra-53 

2.Place the TwitchTV app folder in your home folder !

3.Next check your display resolution !

Do you want to boardcast your full desktop ? This is recommended for boardcasting games ;)

Open your Display Manager and check your res (in my case it's 1920x1080)

4.Open a text editor and open the twitchtv.sh in the TwitchTV app folder 

Write your resolution in the INRES section 

Next is the most importent step for good streaming !

Go to http://www.speedtest.net/ and test your bandwidth speed. The upload speed is IMPORTENT ! 

If your Download speed higher than 6 Mbps than you should use "medium" for boardcast normal quality.

If your Download speed is lower than 6 or between 2 or 3 Mbps you should use "fast" for boardcast lower quality

Now you need to go to http://www.twitch.tv/broadcast/ and copy your Stream Key !

5.Open a new text document in your text editor (gedit or so) paste it in, name it .twitch_key and finally save it in your home folder.

6.Now, right click on the twitchtv.desktop file, open the "Properties" and just tick the "Execute" box in your "Permission" tab to allow it to run on your system.

7.We're done ! Happy boardcasting ! :D
 

 



