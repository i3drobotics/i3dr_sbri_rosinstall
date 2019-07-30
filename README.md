# I3DR SBRI Ros workspace

ROS Workspace for SBRI project

Refer to README in i3dr_sbri for usage of i3dr cameras for SBRI project

Refer to README in isi_base for usage of isi hes probe for SBRI project

## Install

### rosinstall

``` bash
cd /path/to/repo
wstool init src
wstool merge -t src i3dr_sbri.rosinstall
wstool merge -t src isi_sbri.rosinstall
wstool update -t src
```

## I3DR stereo algorithm

I3DR Stereo Algorithm is avaiable on request. This is an SGM matching algorithm.
Install the phobos_integration.deb, this will install the required files to /usr/local/Phobos.
We will provide a license file that must be placed in the folder:

``` bash
/path/to/repo/devel/lib/i3dr_stereo_camera/YOUR_LICENSE.lic
```

## Build

### Catkin Build

``` bash
cd /path/to/repo
catkin_make
```

### I3DR Stereo Algorithm

To build with the I3DR stereo algorithm use the following command:

``` bash
catkin_make -DENABLE_I3DR_ALG=ON
```

## Run

## Source workspace

``` bash
cd /path/to/repo
source devel/setup.sh
```

## i3dr packages

See /i3dr/i3dr_sbri/README.md for details on running i3dr SBRI packages

## isi packages

See /isi/isi_hes_base/README.md for details on running isi SBRI packages
