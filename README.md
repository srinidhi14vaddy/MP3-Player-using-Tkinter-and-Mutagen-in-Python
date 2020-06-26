# MP3-Player-using-Tkinter-and-Mutagen-in-Python
<h3>ABSTRACT</h3><br>
Audio is an important source of communication and is as important as text
in today’s time. We know that the audio files are digital files. Therefore,
there is a need of a tool to run the digital files or in other words, play the
files. Without this tool or player, we’ll never be able to listen to music,
movies or the contents of any audio file. <br>
Thus, we need MP3 players. It is a device using to play MP3s and other
digital audio files. We can build this by ourselves without have to
download and install premium music players. The Mp3 player GUI project
idea attempts to emulate the physical MP3 Player.<br> This program will allow
you to play songs, music, and all MP3 files on your desktop or laptops.
MP3 player using Python is a basic programming application built using
the programming language Python. It is a GUI program built by the means
of Python libraries Tkinter, Pygame and Mutagen.<br>
The MP3 player application should have the capabilities of playing a song,
create and display a playlist, pause and resume a long and change the song,
that is, play the previous or next song. <br>

<h3>INTRODUCTION</h3><br>
We need an application that will allow us to play or listen to digital audio
files. MP3 player is the device to play MP3s and other digital audio files.
The MP3 GUI program application attempts to emulate the physical MP3
Player. This program will allow you to play songs, music, and all MP3
files on your desktop or laptops.<br>
The main objective of this project is to allow users to play MP3 and digital
audio files. To be engaging for users, the application has to have a simple
but beautiful user interface.<br>
This GUI project is developed using Python programming language. The
GUI aspect of the application is built using the Tkinter library of Python.
The interactive part of the application that handles the MP3 files uses the
Pygame and Mutagen libraries.<br>
You can have an interface for listing the available MP3 files. You can also
give users the option to list other digital audio files that are not MP3.
The users will also expect the MP3 Player to have an interface that shows
information on the file that is playing. Some of the information you can
include are the name of the file, its length, the amount played, and the
amount not played, in minutes and seconds.<br>
Python has libraries that can play audio files, such as Pygame, which
allows you to work with multimedia files in few lines of code. Similar
libraries are Pymedia and Simpleaudio. These libraries can handle a lot of
digital audio files. They can handle other file types, not just the MP3 files.
You can also implement a feature that allows users to create a playlist. To
do this, you’ll need a database to store information on the created playlists.
Python’s sqlite3 module allows you to use the SQLite database.<br>
The SQLite database is a better option in this case, because it is file based
and easier to set up than other SQL databases. While SQLite is file
based, it is better for saving data than a regular file.<br>
 
<h3>PROBLEM DESCRIPTION</h3><br>
1. To build an MP3 player using Python programming language to be
able to play and listen to songs, MP3 files and other digital audio
files.<br>
2. Determine the functionalities of the MP3 player.<br>
3. The player should be have a simple and easy to use GUI with
options for various functions, display screen to display the entire
playlist and buttons to shut down the player.<br>
4. The player should be able to play any song. It should be capable of
playing MP3 files or any other digital audio files.<br>
5. The player should allow the user to browse through the contents of
the computer drive to choose song/s to be played or queued.<br>
6. It should provide the user with option to pause or resume the song.<br>
7. The user should be able to play the previous or the next song in the
playlist.<br>
8. Lastly, the user should get basic details about the current playing
song. The details can include the song name, singer’s name, the
duration of the song, size of the file, etc. <br>

<h3>ALGORITHM</h3><br>
1. Import the libraries.<br>
2. Create an object of the tkinter and Pygame libraries.<br>
3. Create a window using Tkinter object.<br>
4. Add buttons that provide different functionalities.<br>
 Add a song<br>
 Play the song<br>
 Pause the song<br>
 Play previous song<br>
 Play next song<br>
5. Add a song button when pressed should open a dialog box to browse and choose the
file.<br>
6. Add label to display the song’s information.<br>
 Name<br>
 Singer<br>
 Duration<br>
 Size of the file, etc.<br>
7. Display screen will display the details of the entire playlist.<br>
8. Close button will automatically clear the song list and will stop playing the song<br>
