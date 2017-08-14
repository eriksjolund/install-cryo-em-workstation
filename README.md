# install-cryo-em-workstation

Step-by-step instructions for installing an Ubuntu workstation with standard cryo-em software.
The installed software should provide tools for post-processing and analyzing experiment data from a [Titan TEM](https://www.fei.com/products/tem/titan/).
The ultimate goal is to have the installation fully automatic by just running a script.

## Software to be installed

* Ubuntu 16.04 LTS desktop (right now 16.04.3 is the latest)
* [relion](http://www2.mrc-lmb.cam.ac.uk/relion/index.php/Main_Page)  
* [chimera](https://www.cgl.ucsf.edu/chimera/)
* [Xmipp](http://xmipp.cnb.csic.es/twiki/bin/view/Xmipp/WebHome)
* [EMAM](http://blake.bcm.edu/emanwiki/EMAN2)
* [ctffind4](http://grigoriefflab.janelia.org/ctffind4)
* [Gctf](http://www.mrc-lmb.cam.ac.uk/kzhang/Gctf/)
* [Gautomatch](http://www.mrc-lmb.cam.ac.uk/kzhang/Gautomatch/)
* [cuda 8](https://en.wikipedia.org/wiki/CUDA)  
* [motioncor2](http://msg.ucsf.edu/em/software/motioncor2.html)
* [localrec](https://github.com/OPIC-Oxford/localrec)

## Hardware requirements

The computer is expected to have 
* at least one recent NVidia card (e.g. GTX 1080, GTX 1070, GTX 1060).

## Step-by-step instructions

A lot of instructions are missing as of now, but let us start writing them.

### Install Ubuntu 16.04 Desktop

Follow the [tutorial](https://tutorials.ubuntu.com/tutorial/tutorial-install-ubuntu-desktop) of how to install an Ubuntu desktop.

### Install Cuda and the nVidia kernel drivers

Cuda and nVidia kernel drivers can be installed in different ways.
Investigate, Which one works best?....

#### graphics-drivers PPA
```
sudo add-apt-repository ppa:graphics-drivers/ppa
sudo apt-get update

```

