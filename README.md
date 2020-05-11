# Picar_2
Continuation of Picar project. 


// Picar2 Notes

$ sudo apt-get update && sudo apt-get upgrade -y

$ sudo reboot now

--------

Raspi-config

$ sudo raspi-config

enable camera, i2c, ssh

--------

Install ROS Kinetic on both devices

ROS.org install instructions

Rpi edit!

https://www.seeedstudio.com/blog/2019/08/01/installing-ros-melodic-on-raspberry-pi-4-and-rplidar-a1m8/

--------

Install Gstreamer

sudo apt-get install gstreamer1.0-tools

--------

Install opencv2 with gstremer support on control pc

https://medium.com/@galaktyk01/how-to-build-opencv-with-gstreamer-b11668fa09c

--------

Install PCA9685 servo controller drivers

https://github.com/adafruit/Adafruit_Python_PCA9685

sudo apt-get install git build-essential python-dev
cd ~
git clone https://github.com/adafruit/Adafruit_Python_PCA9685.git
cd Adafruit_Python_PCA9685
sudo python setup.py install

-------

configure dhcpcd.conf and wpa_supplicant.conf

-------
