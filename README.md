# crazyflie-pc-client-leapmotion
Crazyflie PC clinet + Leapmotion
--------------------------------

It is full example for Crazyflie with connect Leapmotion for Mac OSX. 

Install Python
--------------

1. Install Homebrew<br>
```ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"```

2. Run<br>
```brew doctor```

3. Install Git<br>
```brew install git```

4. Install Python<br>
```brew install python```

5. Setting path<br>
```echo 'export PYTHONPATH=/usr/local/lib/python2.7/site-packages:$PYTHONPATH' >> ~/.bashrc```
```source ~/.bashrc```

6. Install SDL for Python (Simple DirectMedia Layer)<br>
```brew install sdl sdl2 sdl_image sdl_mixer sdl_ttf portmidi```

7. Install dependencies<br>
```brew install pyqt libusb mercurial```<br>
```pip install --pre pysdl2 pyusb pyqtgraph```<br>
```pip install hg+http://bitbucket.org/pygame/pygame```<br>
```pip install pyusb```

Install Leapmotion 
------------------

1. Download LEapmotion SDK - https://developer.leapmotion.com/downloads/skeletal-beta?platform=osx&version=2.2.2.24469
2. In this package install ```Leap_Motion_Installer_release_public_mac_x64_2.2.2+24469_ah1842.dmg```
3. Connect and test Leapmotion sensor

Install Crazyflie PC Client
---------------------------

1. Download repository crazy-pc-client-leapmotion
2. Unpack zip file on disk
3. Run ```crazy-pc-client-leapmotion/bin/cfclient```


