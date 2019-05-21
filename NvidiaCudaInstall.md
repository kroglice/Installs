# Go To Cuda Archive
[Cuda Toolkit Archive](https://developer.nvidia.com/cuda-toolkit-archive)

## Ubuntu 18.04
### Download the *.run
### Add Permitions to the file
```console
sudo chmod 777 ./cuda*
```
### Execute the installer and Follow the Instructions
```console
sudo ./cuda*
```
### Create a file to configure the CUDA environment for all users
```console
sudo vim /etc/profile.d/cuda.sh
```
### Add the following text to the file
```console
export PATH=$PATH:/usr/local/cuda/bin
export CUDADIR=/usr/local/cuda
```
### Create another file
```console
sudo vim /etc/ld.so.conf.d/cuda.conf
```
### Add the following text to the file
```console
/usr/local/cuda/lib64
```
### Execute the following command
```console
sudo ldconfig
```
### Or __Optionaly__ add the following commands to your .bashrc
```console
export PATH=$PATH:/usr/local/cuda-10.0/bin
export CUDADIR=/usr/local/cuda-10.0
export LD_LIBRARY_PATH=$LD_LIBRARY_PATH:/usr/local/cuda-10.0/lib64
```
