# TwitchBot
My very own Twitch Bot

This file will go through the files of my twitch bot

My Twitch bot uses a mIRC server to excecute the code in the folde "Code".
The code generally won't work without the mIRC librabry or the necessary variables that come with the program.

In the ".TXT files" you can find the textfiles the code reads out of and writes input into from the chat. 

Remote.ini -> contains greeting commands using greeting.txt & emote.txt
script1.ini -> contains a Quote system using quotes.txt to store the quotes

script2.ini -> contains a timeout for certain link formats

script3.ini -> contains a timed message that can be turned on and off, it uses timed.txt to get the content

script4.ini -> contains a point system, that uses Points.ini to store the username + points of a user

script5.ini -> contains a all commands command that shows all commands upon typing !commands or !modcommands

script6.ini -> contains a contains an easter egg "Kappa counter" which counts all the Kappa emotes spammed since the bot went online

script7.ini -> contains a add greetings command, that allows a mod to add a greeting if someone uses one that isn't in the greeting.txt