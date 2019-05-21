# Installation of Nvidia Drivers
## Ubuntu 18.04

### Clean the system of other Nvidia drivers
```console
sudo apt purge nvidia*
```
### Add the Nvidia graphic card PPA
```console
sudo add-apt-repository ppa:graphics-drivers/ppa
sudo apt update
```
### Identify your graphic card model and recommended driver
```console
ubuntu-drivers devices
```
### Install the Nvidia GPU driver
```console
sudo ubuntu-drivers autoinstall
sudo reboot
nvidia-smi
```
or
```console
sudo apt install nvidia-[VERSION-NUMBER]
sudo reboot
nvidia-smi
```
