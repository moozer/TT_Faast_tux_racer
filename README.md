TT_Faast_tux_racer
==================

TT about how to use Tux racer with kinect+FAAST


Purpose
-------
This TT is about using the kinect to generate keyboard and mouse events. Specifically, we install tux racer and use FAAST to generate the events. It could be *any* program provided it doesn't use too many events (try googling FAAST anf World of warcraft)

Requirements
------------
* A pc (or other) running windows 7

    It has been developped on windows 7 + SP1. You probably need administrative rigths,
  
* A kinect
* Internet access

HowTo
-----
1. Download the kinect SDK from http://download.microsoft.com/download/E/E/2/EE2D29A1-2D5C-463C-B7F1-40E4170F5E2C/KinectSDK-v1.0-Setup.exe and run it

    It will ask to install dependencies like _.net framework 4_ and _visual c++ 2010 runtime libraries + SP1_. You need those, so just accept it.
    
2. Do a preemtive reboot
    
3. Download FAAST from http://projects.ict.usc.edu/mxr/wp-content/uploads/2012/04/FAAST-1.0.zip and unzip it

    This TT was done with FAAST version 1.0.0
    
    Do yourself a favor and create a shortcut to FAAST on the desktop

4. Download tux racer from http://download.sourceforge.net/tuxracer/tuxracer-win32-0.61a.zip and unzip it

    Do a test run to make sure that you find it addicting :-)
    
    Again, put a shortcut on the desktop.

5. grab the xml file from this TT

6. Start FAAST, connect to the kinect, and load the xml file

    You should now be able to see yourself and some lines signifying your detected skeleton

7. In FAAST, start emulator

    In the text box, you will see lines like _TUX RIGHT activated_. That means it works.

8. Launch Tux racer and start playing.


Resources used
--------------
* FAAST homepage: http://projects.ict.usc.edu/mxr/faast/
* Kinect for windows homepage: http://www.microsoft.com/en-us/kinectforwindows/develop/overview.aspx
* Tux racer homepage http://tuxracer.sourceforge.net/

Cred
----
To Lucian for doing the actual work

Question?
---------
send me an email bigmoozer@gmail.com
