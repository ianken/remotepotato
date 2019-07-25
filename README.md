remotepotato
============
Remote Potato Server - a free streaming server to stream all media on a PC to browsers, apps, etc
See www.remotepotato.com

Readme Update: This fork addresses a few issues with the original solution: namely the hard coded 25Hz frame rate for video. 

LOL. Should have added this comment a few years ago.


Build Instructions
==================
Remote Potato is a Visual Studio 2010 solution file. 
For Media Center support, you should build Remote Potato on a machine that has Windows 7 Media Center installed so that the required Microsoft libraries mcstore.dll and mcepg.dll can be accessed from their locations in c:\windows\ehome
Build the solution first, then right-click and build the integrated RemotePotatoSetup project

Developer Notes
===============
Before doing anything, you should take a look at the class overview document contained within the root folder; here you will find information as to where to begin.

Issues etc
==========
This is an initial release, there may be ommissions - please let me know of anything important via Github

Project Maintenance
===================
We are looking for people to maintain and develop this project - please get in touch if you are interested by emailing me - carl at remotepotato dot com

Licence
=======
ANY use of the Remote Potato Server source code is under GPL licence version 3 - see http://www.gnu.org/copyleft/gpl.html

Thanks!

Carlos

