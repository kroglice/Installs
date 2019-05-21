# Go To CudNN Archive
[Cudnn Archive](https://developer.nvidia.com/rdp/cudnn-archive)
## Ubuntu 18.04

### Unzip the File
```console
tar -xzvf cudnn-*.tgz
```
### Run the Following Commands
```console
sudo cp cuda/include/cudnn.h /usr/local/cuda/include
sudo cp cuda/lib64/libcudnn* /usr/local/cuda/lib64
sudo chmod a+r /usr/local/cuda/include/cudnn.h /usr/local/cuda/lib64/libcudnn*
```
