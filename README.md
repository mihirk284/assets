# assets

This repository contains all models and worlds required by the JdeRobot exercises. An effort has been made to have minimal new models and reuse the official models as much as possible. This is due to the fact that any models that are available through the official sources and are not available in the system are automatically downloaded and saved for future usage (This does mean that the first time boot may be much slower - depending on one's internet connection)

The `kinetic-devel` branch has been released on the official ROS build farm and can be downloaded using the command:

```bash
sudo apt-get install ros-kinetic-jderobot-assets
```


The `master` branch has been released on the official ROS build farm and can be downloaded using the command:

```bash
sudo apt-get install ros-melodic-jderobot-assets
```
<br />

## ROS Distro Support

|         | Kinetic | Melodic |
|:-------:|:-------:|:-------:|
| Branch  | [`kinetic-devel`](https://github.com/JdeRobot/assets/tree/kinetic-devel) | [`master`](https://github.com/JdeRobot/assets/tree/master)
| Status  |  supported | supported |
| Version | [version](http://repositories.ros.org/status_page/ros_kinetic_default.html?q=jderobot_assets) | [version](http://repositories.ros.org/status_page/ros_melodic_default.html?q=jderobot_assets) |

<br /><br />

**ROS Version – Distro**|**Dev-amd64**|**src**|**Bin-32**|**Bin-64**|**Bin-armhf**|**Bin-arm64**
:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:
Kinetic – Xenial|[![Build Status](http://build.ros.org/job/Kdev__jderobot_assets__ubuntu_xenial_amd64/badge/icon)](http://build.ros.org/job/Kdev__jderobot_assets__ubuntu_xenial_amd64/)|[![Build Status](http://build.ros.org/job/Kdev__jderobot_assets__ubuntu_xenial_amd64/badge/icon)](http://build.ros.org/job/Kdev__jderobot_assets__ubuntu_xenial_amd64/) | [![Build Status](http://build.ros.org/job/Kbin_uX32__jderobot_assets__ubuntu_xenial_i386__binary/badge/icon)](http://build.ros.org/job/Kbin_uX32__jderobot_assets__ubuntu_xenial_i386__binary/) | [![Build Status](http://build.ros.org/job/Kbin_uxhf_uXhf__jderobot_assets__ubuntu_xenial_armhf__binary/badge/icon)](http://build.ros.org/job/Kbin_uxhf_uXhf__jderobot_assets__ubuntu_xenial_armhf__binary/) |  [![Build Status](http://build.ros.org/job/Kbin_uxhf_uXhf__jderobot_assets__ubuntu_xenial_armhf__binary/badge/icon)](http://build.ros.org/job/Kbin_uxhf_uXhf__jderobot_assets__ubuntu_xenial_armhf__binary/) | [![Build Status](http://build.ros.org/job/Kbin_uxv8_uXv8__jderobot_assets__ubuntu_xenial_arm64__binary/badge/icon)](http://build.ros.org/job/Kbin_uxv8_uXv8__jderobot_assets__ubuntu_xenial_arm64__binary/)
Melodic – Bionic| [![Build Status](http://build.ros.org/job/Mdev__jderobot_assets__ubuntu_bionic_amd64/badge/icon)](http://build.ros.org/job/Mdev__jderobot_assets__ubuntu_bionic_amd64/)| [![Build Status](http://build.ros.org/job/Msrc_uB__jderobot_assets__ubuntu_bionic__source/badge/icon)](http://build.ros.org/job/Msrc_uB__jderobot_assets__ubuntu_bionic__source/) | N.A. | [![Build Status](http://build.ros.org/job/Mbin_uB64__jderobot_assets__ubuntu_bionic_amd64__binary/badge/icon)](http://build.ros.org/job/Mbin_uB64__jderobot_assets__ubuntu_bionic_amd64__binary/)  |  [![Build Status](http://build.ros.org/job/Mbin_ubhf_uBhf__jderobot_assets__ubuntu_bionic_armhf__binary/badge/icon)](http://build.ros.org/job/Mbin_ubhf_uBhf__jderobot_assets__ubuntu_bionic_armhf__binary/) |  [![Build Status](http://build.ros.org/job/Mbin_dsv8_dSv8__jderobot_assets__debian_stretch_arm64__binary/badge/icon)](http://build.ros.org/job/Mbin_dsv8_dSv8__jderobot_assets__debian_stretch_arm64__binary/)
Debian - Stretch | N.A. | [![Build Status](http://build.ros.org/job/Msrc_dS__jderobot_assets__debian_stretch__source/badge/icon)](http://build.ros.org/job/Msrc_dS__jderobot_assets__debian_stretch__source/) | N.A. |  [![Build Status](http://build.ros.org/job/Mbin_ds_dS64__jderobot_assets__debian_stretch_amd64__binary/badge/icon)](http://build.ros.org/job/Mbin_ds_dS64__jderobot_assets__debian_stretch_amd64__binary/)  | N.A. | [![Build Status](http://build.ros.org/job/Mbin_dsv8_dSv8__jderobot_assets__debian_stretch_arm64__binary/badge/icon)](http://build.ros.org/job/Mbin_dsv8_dSv8__jderobot_assets__debian_stretch_arm64__binary/)
