# pal_mobile_base_docker (Noetic)

This package contains the Noetic Dockerfile for TIAGo Base (PMB2), TIAGo OMNI Base and ARan Base (PMB3) online tutorials.

**Important Note: This Dockerfile is meant to be used to explore the functionalities of PAL Robotics mobile bases, it is not meant for development on the real robots since more functionalities are available in the dockers provided to customers when purchasing a robot.**

You can find the Dockerfile corresponding to each ROS distribution in its respective branch.

To use this Docker you can either:

- Build it locally with the latest version of all our packages

or

- Pull the already build image from DockerHub

## Building your docker locally

```
cd pal_mobile_base_docker

docker build --no-cache -t pal_mobile_base_noetic_docker .
```
## Pulling Image

The image can be pulled from [DockeHub](https://hub.docker.com/r/palroboticssl/pal_mobile_base_tutorials) : 

```
docker pull palroboticssl/pal_mobile_base_tutorials:noetic
```

## Tutorials

The tutorials that can be followed thanks to this Docker are listed here:
* TIAGo Base: [http://wiki.ros.org/Robots/PMB-2/Tutorials](http://wiki.ros.org/Robots/PMB-2/Tutorials)
* TIAGo OMNI Base: [http://wiki.ros.org/Robots/TIAGo-OMNI-base/Tutorials](http://wiki.ros.org/Robots/TIAGo-OMNI-base/Tutorials)
* ARan Base: [http://wiki.ros.org/Robots/TIAGo-OMNI-base/Tutorials](http://wiki.ros.org/Robots/TIAGo-OMNI-base/Tutorials)

## Git Repo & Bugtracker

If issues are encountered during those tutorials please open an issue on the appropriate repository.

### TIAGo Base (PMB2)
* **Repository**: [https://github.com/pal-robotics/pmb2_tutorials](https://github.com/pal-robotics/pmb2_tutorials/tree/noetic-devel)
* **Bugtracker**: [https://github.com/pal-robotics/pmb2_tutorials/issues](https://github.com/pal-robotics/pmb2_tutorials/issues)

### TIAGo OMNI Base
* **Repository**: [https://github.com/pal-robotics/omni_base_tutorials](https://github.com/pal-robotics/omni_base_tutorials/tree/noetic-devel)
* **Bugtracker**: [https://github.com/pal-robotics/omni_base_tutorials/issues](https://github.com/pal-robotics/omni_base_tutorials/issues)

### ARan Base (PMB3)
* **Repository**: [https://github.com/pal-robotics/pmb3_tutorials/tree/noetic-devel](https://github.com/pal-robotics/pmb3_tutorials/tree/noetic-devel)
* **Bugtracker**: [https://github.com/pal-robotics/pmb3_tutorials/issues](https://github.com/pal-robotics/pmb3_tutorials/issues)