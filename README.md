# I3DR SBRI Ros workspace

ROS Workspace for SBRI project

## WARNING Repositor is still being setup. Please check back later

## Install

### rosinstall

``` bash
wstool merge -t src ~/PATH_TO_REPO/src/i3dr_sbri.rosinstall
wstool merge -t src ~/PATH_TO_REPO/src/isi_sbri.rosinstall
```

### I3DR stereo algorithm

I3DR Stereo Algorithm is avaiable on request. This is an SGM matching algorithm.
Install the phobos_integration.deb, this will install the required files to /usr/local/Phobos.
We will provide a license file that must be placed in the folder:

``` bash
/PATH_TO_REPO/devel/lib/i3dr_stereo_camera/YOUR_LICENSE.lic
```

## Build

### I3DR Stereo Algorithm

To build with the I3DR stereo algorith use the following command:

``` bash

```
