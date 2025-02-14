# ArduPilot Project

<a href="https://ardupilot.org/discord"><img src="https://img.shields.io/discord/674039678562861068.svg" alt="Discord">

![Test Copter](https://github.com/ArduPilot/ardupilot/workflows/test%20copter/badge.svg?branch=master) ![Test Plane](https://github.com/ArduPilot/ardupilot/workflows/test%20plane/badge.svg?branch=master) ![Test Rover](https://github.com/ArduPilot/ardupilot/workflows/test%20rover/badge.svg?branch=master) ![Test Sub](https://github.com/ArduPilot/ardupilot/workflows/test%20sub/badge.svg?branch=master) ![Test Tracker](https://github.com/ArduPilot/ardupilot/workflows/test%20tracker/badge.svg?branch=master)

![Test AP_Periph](https://github.com/ArduPilot/ardupilot/workflows/test%20ap_periph/badge.svg?branch=master) ![Test Chibios](https://github.com/ArduPilot/ardupilot/workflows/test%20chibios/badge.svg?branch=master) ![Test Linux SBC](https://github.com/ArduPilot/ardupilot/workflows/test%20Linux%20SBC/badge.svg?branch=master) ![Test Replay](https://github.com/ArduPilot/ardupilot/workflows/test%20replay/badge.svg?branch=master)

![Test Unit Tests](https://github.com/ArduPilot/ardupilot/workflows/test%20unit%20tests/badge.svg?branch=master)

[![Build SemaphoreCI](https://semaphoreci.com/api/v1/ardupilot/ardupilot/branches/master/badge.svg)](https://semaphoreci.com/ardupilot/ardupilot) [![Build Status](https://dev.azure.com/ardupilot-org/ardupilot/_apis/build/status/ArduPilot.ardupilot?branchName=master)](https://dev.azure.com/ardupilot-org/ardupilot/_build/latest?definitionId=1&branchName=master)

[![Coverity Scan Build Status](https://scan.coverity.com/projects/5331/badge.svg)](https://scan.coverity.com/projects/ardupilot-ardupilot)

[![Autotest Status](https://autotest.ardupilot.org/autotest-badge.svg)](https://autotest.ardupilot.org/)

Ardupilot is the most advanced, full-featured and reliable open source autopilot software available. It has
been under development since 2010 by a diverse team of professional engineers, computer scientists and community contributors.
Our autopilot software is capable of controlling almost any vehicle system imaginable, from conventional
airplanes, quadplanes, multirotors, and helicopters, to rovers, boats, balancebots and even submarines. It is continually being expanded to provide
support for new emerging vehicle types.

## The ArduPilot project is made up of: ##

- ArduCopter: [code](https://github.com/ArduPilot/ardupilot/tree/master/ArduCopter), [wiki](https://ardupilot.org/copter/index.html)

- ArduPlane: [code](https://github.com/ArduPilot/ardupilot/tree/master/ArduPlane), [wiki](https://ardupilot.org/plane/index.html)

- Rover: [code](https://github.com/ArduPilot/ardupilot/tree/master/Rover), [wiki](https://ardupilot.org/rover/index.html)

- ArduSub : [code](https://github.com/ArduPilot/ardupilot/tree/master/ArduSub), [wiki](http://ardusub.com/)

- Antenna Tracker : [code](https://github.com/ArduPilot/ardupilot/tree/master/AntennaTracker), [wiki](https://ardupilot.org/antennatracker/index.html)

## User Support & Discussion Forums ##

- Support Forum: <https://discuss.ardupilot.org/>

- Community Site: <https://ardupilot.org>

## Developer Information ##

- Github repository: <https://github.com/ArduPilot/ardupilot>

- Main developer wiki: <https://ardupilot.org/dev/>

- Developer discussion: <https://discuss.ardupilot.org>

- Developer chat: <https://discord.com/channels/ardupilot>

## Top Contributors ##

- [Flight code contributors](https://github.com/ArduPilot/ardupilot/graphs/contributors)
- [Wiki contributors](https://github.com/ArduPilot/ardupilot_wiki/graphs/contributors)
- [Most active support forum users](https://discuss.ardupilot.org/u?order=post_count&period=quarterly)
- [Partners who contribute financially](https://ardupilot.org/about/Partners)

## How To Get Involved ##

- The ArduPilot project is open source and we encourage participation and code contributions: [guidelines for contributors to the ardupilot codebase](https://ardupilot.org/dev/docs/contributing.html)

- We have an active group of Beta Testers to help us improve our code: [release procedures](https://dev.ardupilot.org/wiki/release-procedures)

- Desired Enhancements and Bugs can be posted to the [issues list](https://github.com/ArduPilot/ardupilot/issues).

- Help other users with log analysis in the [support forums](https://discuss.ardupilot.org/)

- Improve the wiki and chat with other [wiki editors on Gitter](https://gitter.im/ArduPilot/ardupilot_wiki)

- Contact the developers on one of the [communication channels](https://ardupilot.org/copter/docs/common-contact-us.html)

## License ##

The ArduPilot project is licensed under the GNU General Public
License, version 3.

- [Overview of license](https://dev.ardupilot.com/wiki/license-gplv3)

- [Full Text](https://github.com/ArduPilot/ardupilot/blob/master/COPYING.txt)

## Maintainers ##

ArduPilot is comprised of several parts, vehicles and boards. The list below
contains the people that regularly contribute to the project and are responsible
for reviewing patches on their specific area.

- [Andrew Tridgell](https://github.com/tridge):
  - ***Vehicle***: Plane, AntennaTracker
  - ***Board***: APM1, APM2, Pixhawk, Pixhawk2, PixRacer
- [Francisco Ferreira](https://github.com/oxinarf):
  - ***Bug Master***
- [Grant Morphett](https://github.com/gmorph):
  - ***Vehicle***: Rover
- [Jacob Walser](https://github.com/jaxxzer):
  - ***Vehicle***: Sub
- [Lucas De Marchi](https://github.com/lucasdemarchi):
  - ***Subsystem***: Linux
- [Michael du Breuil](https://github.com/WickedShell):
  - ***Subsystem***: Batteries
  - ***Subsystem***: GPS
  - ***Subsystem***: Scripting
- [Peter Barker](https://github.com/peterbarker):
  - ***Subsystem***: DataFlash, Tools
- [Randy Mackay](https://github.com/rmackay9):
  - ***Vehicle***: Copter, Rover, AntennaTracker
- [Tom Pittenger](https://github.com/magicrub):
  - ***Vehicle***: Plane
- [Bill Geyer](https://github.com/bnsgeyer):
  - ***Vehicle***: TradHeli
- [Chris Olson](https://github.com/ChristopherOlson):
  - ***Vehicle***: TradHeli
- [Emile Castelnuovo](https://github.com/emilecastelnuovo):
  - ***Board***: VRBrain
- [Eugene Shamaev](https://github.com/EShamaev):
  - ***Subsystem***: CAN bus
  - ***Subsystem***: UAVCAN
- [Georgii Staroselskii](https://github.com/staroselskii):
  - ***Board***: NavIO
- [Gustavo José de Sousa](https://github.com/guludo):
  - ***Subsystem***: Build system
- [Julien Beraud](https://github.com/jberaud):
  - ***Board***: Bebop & Bebop 2
- [Leonard Hall](https://github.com/lthall):
  - ***Subsystem***: Copter attitude control and navigation
- [Matt Lawrence](https://github.com/Pedals2Paddles):
  - ***Vehicle***: 3DR Solo & Solo based vehicles
- [Matthias Badaire](https://github.com/badzz):
  - ***Subsystem***: FRSky
- [Mirko Denecke](https://github.com/mirkix):
  - ***Board***: BBBmini, BeagleBone Blue, PocketPilot
- [Paul Riseborough](https://github.com/priseborough):
  - ***Subsystem***: AP_NavEKF2
  - ***Subsystem***: AP_NavEKF3
- [Pierre Kancir](https://github.com/khancyr):
  - ***Subsystem***: Copter SITL, Rover SITL
- [Víctor Mayoral Vilches](https://github.com/vmayoral):
  - ***Board***: PXF, Erle-Brain 2, PXFmini
- [Amilcar Lucas](https://github.com/amilcarlucas):
  - ***Subsystem***: Marvelmind
- [Samuel Tabor](https://github.com/samuelctabor):
  - ***Subsystem***: Soaring/Gliding
# Ubuntu Setup
Please install Ubuntu in virtual machine or linux system. Ubuntu 18.04 is recommended.
## Setting up Git command line
    Plese run such codes to insall with apt:
        
        sudo apt-get update
        sudo apt-get install git
        sudo apt-get install gitk git-gui
        
## Clone this repository 
    by following code:
    
        git clone https://github.com/xpan11/Arducopter
        cd Arducopter
        git submodule update --init --recursive
 
## Install required packages:
    for Ubuntu and Mint user, type following line in terminal from Arducopter director will install automatically:
        Tools/environment_install/install-prereqs-ubuntu.sh -y
    then reload the path by typing:
        . ~/.profile
## Cleaning
    to do a full clean build, type such command in terminal:
        ./waf configure
        ./waf clean
# Runing the program
## Start the vehicle simulator
    To normally run the vehicle simulator with map and console, type following code in terminal:
        sim_vehicle.py -v VEHICLE --console --map
    for example:
        sim_vehicle.py -v ArduCopter --console --map
    for more information, please visit Ardupilot website:
        https://ardupilot.org/dev/docs/using-sitl-for-ardupilot-testing.html
## Get the vehicle moving
ArduCopter have more than 15 modes, here I will demostrate two of our frequent used modes.
## STABLIZE Mode
STABLIZE Mode only take action by reciving meassage of RC channel, which is a channel that takes user inputs. Some of important channel ID are list below base on the offical website of Ardupilot:
    
![New VM](./pics/rc_channels.png)
 
To control the copter in stabilize mode, is to set paramters base on corespoding RC channels in format of "rc channel_id value". 
for example, to let the copter vertical takeoff (only modify throttle. Yaw, pitch and roll angles stay 0):
![New VM](./pics/sta_takeoff.png)

 for another example, to let the copter moving up forward (only modify throttle and pitch angle.Yaw and roll angles stay 0):   
 ![New VM](./pics/sta_upforward.png)
 
## GUIDED mode
The defult mode of arducopter is stablize mode, first to switch to GUIDED mode:

![New VM](./pics/switch_mode.png)

Always remember to arm throttle before takeoff:

![New VM](./pics/gui_takeoff.png)

here, command "takeoff 100" means take off and keep going up vertically till reach 100m high.

Since it is GUIDED mode, so it will guide itself to position set by user, by doing that:

click the position you would like to go in the map with right mouse:

![New VM](./pics/gui_fly.png)

select "fly to" and it will pop up a height setting window, you can set what height of the destination:
![New VM](./pics/gui_set.png)

After setting, it will drive itself to the desitination:
![New VM](./pics/gui_gui.png)



    




    
        
        
    
 
    
