
[TOC]


# Firmware update log

## 2020-05-16 
**AIO-3399C-AI-UBUNTU18.04-GPT-20200516-1556.img.7z**

* NAME： AIO-3399J-UBUNTU18.04-GPT-20200516-1304.img.7z
* COMMIT： f3ff609bcd46a36219a7865b0425b4eab990000d
* MD5： 1a9ff82d7194820fec9c1186e1890c5e
* FS: ubuntu_18.04_arm64_ext4_v2.02-31-g40127b8_20200512-1048_DESKTOP.img + 

**AIO-3399C-AI-LVDS-UBUNTU18.04-GPT-20200516-1601.img.7z**

* NAME： AIO-3399J-UBUNTU18.04-GPT-20200516-1304.img.7z
* COMMIT： f3ff609bcd46a36219a7865b0425b4eab990000d
* MD5： 944f014c16ea9ba01c6d00720281a8f8
* FS: ubuntu_18.04_arm64_ext4_v2.02-31-g40127b8_20200512-1048_DESKTOP.img

**Update content:**
* kernel:
1. remove isp video device when no mipi camera connect
2. enable framebuffer console

* FS:
1. Install libopencv-contrib-dev
2. Install firefly-multi-rtsp
3. Install firefly-3399pronpu-driver
4. Fix mipi camera preview issue
5. System startup related issues