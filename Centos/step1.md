Let's build a CentOS 7 base image.

Procedure

Create a directory and navigate to it

`mkdir -p ~/src/base_images.`{{execute}}

`cd ~/src/base_images.`{{execute}}

Retrieve the BlueData base image for CentOS 7

`bdwb --baseimg centos7`{{execute}}

Navigate to CentOS7 directory

`cd centos7`{{execute}}

List of contents

`ls -a`{{execute}}

Execute the following commands

`export BASE_IMG_ORGNAME='sds'`{{execute}}

`export BASE_IMG_VERSION='1.0'`{{execute}}

`export CENTOS7_UPSTREAM='centos:centos7'`{{execute}}

Create the image

`make centos7`{{execute}}

Verify

`docker images`{{execute}}
