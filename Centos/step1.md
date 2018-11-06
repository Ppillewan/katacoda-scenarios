Let's build a simple application.

## Task 1 of 6
Step 1
`mkdir -p ~/src/base_images.`{{execute}}

`cd ~/src/base_images.`{{execute}}

`bdwb --baseimg centos7`{{execute}}

`cd centos7`{{execute}}

`ls -a`{{execute}}

`export BASE_IMG_ORGNAME='sds'`{{execute}}

`export BASE_IMG_VERSION='1.0'`{{execute}}

`export CENTOS7_UPSTREAM='centos:centos7'`{{execute}}

`make centos7`{{execute}}

`docker images`{{execute}}
