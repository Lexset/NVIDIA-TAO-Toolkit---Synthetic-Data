Prerequisites:

NVIDIA TAO Toolkit requires an NVIDIA graphics card and driver to use their docker container, so you must have one to proceed. At least 16 GBs physical RAM, 50 GB of available memory, and an 8 Core CPU are needed to run this successfully. We tested on Python 3.6.9, and used UBUNTU 18.04. TAO Toolkit requires NVIDIA driver 455.xx or later.

The tao-launcher is strictly a python3 only package, capable of running on python 3.6.9 or 3.7 or 3.8.
Install docker-ce by following the official instructions at the link below.
https://docs.docker.com/engine/install.
Once you have installed docker-ce, follow the post-installation steps to ensure that the docker can be run without sudo at the link below.
https://docs.docker.com/engine/install/linux-postinstall/
Install nvidia-container-toolkit by following the install-guide at the link below.
https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/install-guide.html 
You must have an NGC account and an API key associated with your account. See the Installation Prerequisites section for details on creating an NGC account and obtaining an API key.
