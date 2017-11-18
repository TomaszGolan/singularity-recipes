# Singularity Recipes Collection

## Caffe + Ubuntu 14.04 + CUDA 7 + cuDNN 3

1. to build the container

    * grab [caffe-ubuntu14.04-cuda7-cudnn3.def](https://raw.githubusercontent.com/TomaszGolan/singularity-recipes/master/caffe-ubuntu14.04-cuda7-cudnn3.def) and [NVIDIA-Linux-x86_64-375.26.run](http://www.nvidia.com/object/linux-amd64-display-archive.html)

    * and run

    ```
    sudo singularity build caffe-ubuntu14.04-cuda7-cudnn3.img caffe-ubuntu14.04-cuda7-cudnn3.def
    ```

2. to run Caffe simply

    ```
    ./caffe-ubuntu14.04-cuda7-cudnn3.img
    ```