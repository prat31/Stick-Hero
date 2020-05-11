# Stick-Hero
Stick Hero is a fairly simple *Android* game which can be downloader from <a href="https://play.google.com/store/apps/details?id=com.ketchapp.stickhero&hl=en_IN" alt="here">

The python script requires three libraries : 
1. ppadb (Pure Python ADB)
2. Pillow
3. numpy

Please make sure that the android device is connected to the computer and USB Debugging is enabled and paired with the system too.


**stickHero.py** is a simple python program which takes a screenshot of the game window every 2.5 seconds, calculates the distance between the two black pillars, and then sends a *touch* command to the device for the appropriate time period to make the perfectly long stick.


P.S - According to your screen resolution, the row of the image-into-matrix we are concerning with in the program
can change. You may have to find the perfect row for your screen resolution.
Tutorial - https://www.youtube.com/watch?v=Du__JfXqsAs