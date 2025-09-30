# Utility server node
Util is our utilities node for tasks like uploading files to our DISCO2 satellite. 

## Prerequisites

To build util, the following packages are required:
```
sudo apt install libcurl4-openssl-dev git build-essential libsocketcan-dev can-utils libzmq3-dev libyaml-dev pkg-config fonts-powerline python3-pip libelf-dev libbsd-dev libprotobuf-c-dev brotli libbrotli-dev
sudo pip3 install meson ninja
```

## Build Util
To build the project, run the following commands:
```
meson setup . builddir
ninja -C builddir
```
or simply execute the script `./configure_run`.
