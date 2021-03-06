CheesyVision
============

This project can be used to signal your robot during autonomous mode using computer vision and the webcam on your driver station laptop. This is very similar to the Kinect but requires no extra hardware or USB ports.

To run the program, simply install the dependencies listed below (if using Linux or Mac OS X, you can get these packages via apt or homebrew).  Then, double click the cheesyvision.py icon to launch the program (if you want it to communicate with your robot, edit the source code so that it tries to connect to your teams' cRIO).

##Requirements

1. ####Python 2.7
  - Installers found at: https://www.python.org/download/
  - 32 bit: https://www.python.org/ftp/python/2.7.6/python-2.7.6.msi
  - 64 bit: https://www.python.org/ftp/python/2.7.6/python-2.7.6.amd64.msi

2. ####NumPy
  - Installers found at: http://www.lfd.uci.edu/~gohlke/pythonlibs/#numpy
  - 32 bit: https://www.dropbox.com/s/aeusld7lffrawgy/numpy-MKL-1.8.1.win32-py2.7.exe
  - 64 bit: https://www.dropbox.com/s/qzezri6zlteozqe/numpy-MKL-1.8.1.win-amd64-py2.7.exe

3. ####OpenCV
  - Installers found at: http://www.lfd.uci.edu/~gohlke/pythonlibs/#opencv
  - 32 bit: https://www.dropbox.com/s/lb3kkrht0g63nkc/opencv-python-2.4.8.1.win32-py2.7.exe
  - 64 bit: https://www.dropbox.com/s/t6qs8yde326grf4/opencv-python-2.4.8.1.win-amd64-py2.7.exe

3. ####pyNetworkTables
  - Installers found at: http://firstforge.wpi.edu/sf/frs/do/viewRelease/projects.robotpy/frs.pynetworktables.2014_4
  - 32 bit: http://firstforge.wpi.edu/sf/frs/do/downloadFile/projects.robotpy/frs.pynetworktables.2014_4/frs1955;jsessionid=9025B40AA50A7405E7F9EC3B894F829E?dl=1
  - 64 bit: http://firstforge.wpi.edu/sf/frs/do/downloadFile/projects.robotpy/frs.pynetworktables.2014_4/frs1957;jsessionid=9025B40AA50A7405E7F9EC3B894F829E?dl=1

##Legality

  First Q & A
  - Q431 https://frc-qa.usfirst.org/Question/431/questionlink
  - Q446 https://frc-qa.usfirst.org/Question/446/questionlink

##Installation

1. ####Download all requirements and install in the following order:
  - Python 2.7
  - NumPy
  - OpenCV
  - pyNetworkTables

2. Run "cheesyvision (competition).py"

##Notes

If you want to run CheesyVision locally or without a cRIO, follow the steps below:

1. ####Open and run "NT Local Server.vi"

2. ####Open RoboRealm and run "NT Client.robo"

3. ####Run "cheesyvision (localhost).py"

4. ####Switch to the RoboRealm Window to see the variables in the NT