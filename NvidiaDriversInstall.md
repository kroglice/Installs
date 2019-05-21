# Installation of Nvidia Drivers
## Ubuntu 18.04

### Clean the system of other Nvidia drivers
sudo apt purge nvidia*

### Add the Nvidia graphic card PPA
sudo add-apt-repository ppa:graphics-drivers
sudo apt update

### Install the Nvidia GPU driver
sudo apt-get install nvidia-[VERSION-NUMBER]
sudo reboot
nvidia-smi
