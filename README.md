# crazyflie-pc-client-leapmotion
Crazyflie PC clinet + Leapmotion
--------------------------------

It is full example for Crazyflie with connect Leapmotion for Mac OSX. 

Install Python
--------------

1. Install Homebrew<br>
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

2. Run:
brew doctor

3. Install Git
brew install git

4. Install Python
brew install python

5. Setting path
echo 'export PYTHONPATH=/usr/local/lib/python2.7/site-packages:$PYTHONPATH' >> ~/.bashrc
source ~/.bashrc

6. Install SDL for Python (Simple DirectMedia Layer)
brew install sdl sdl2 sdl_image sdl_mixer sdl_ttf portmidi

7. Install dependencies
brew install pyqt libusb mercurial
pip install --pre pysdl2 pyusb pyqtgraph
pip install hg+http://bitbucket.org/pygame/pygame
pip install pyusb


