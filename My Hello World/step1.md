Let's build a simple application.

## Task 1 of 6
`yum install -y python-pip`{{execute}}

`pip install --upgrade pip`{{execute}}

`pip install --upgrade setuptools`{{execute}}

`pip install --upgrade requests`{{execute}}

`pip install --upgrade argparse`{{execute}}

`pip install --upgrade bdworkbench`{{execute}}

`yum install -y epel-release`{{execute}}

`yum install -y python-requests python-setuptools python-argparse python-pip`{{execute}}

Step 1

`yum install -y git`{{execute}}

## Task 2 of 6
Step 2

`mkdir /tmp/samples`{{execute}}
## Task 3 of 6
Step 3

`cd /tmp/samples`{{execute}}

## Task 4 of 6
Step 4

`git clone -b ImageSamples https://github.com/bluedatainc/solutions.git`{{execute}}


## Task 5 of 6
Step 5

`cd solutions/ImageSamples/helloWorld-auto`{{execute}}

`mkdir -p ~/src/catalog/helloworld`{{execute}}

`cd ~/src/catalog/helloworld`{{execute}}

`bdwb --init`{{execute}}

`ls -R`{{execute}}

`mkdir ~/src/catalog/helloworld/image/centos`{{execute}}

`cp /tmp/samples/solutions/ImageSamples/helloWorld-auto/image/centos/Dockerfile  ~/src/catalog/helloworld/image/centos/`{{execute}}

`cat ~/src/catalog/helloworld/image/centos/Dockerfile`{{execute}}

`cp /tmp/samples/solutions/ImageSamples/helloWorld-auto/helloworld-app.wb ~/src/catalog/helloworld`{{execute}}

`cat -n ~/src/catalog/helloworld/helloworld-app.wb | more`{{execute}}

`cp  /tmp/samples/solutions/ImageSamples/helloWorld-auto/appconfig/index.html ~/src/catalog/helloworld/appconfig/`{{execute}}

`cat ~/src/catalog/helloworld/appconfig/index.html`{{execute}}

`cp  /tmp/samples/solutions/ImageSamples/helloWorld-auto/helloworld-logo.png ~/src/catalog/helloworld/`{{execute}}

`./helloworld-app.wb`{{execute}}

`cat staging/helloworld-centos.json`{{execute}}

`cd deliverables`{{execute}}

`ls`{{execute}}

Congrats!
