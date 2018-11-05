Let's build a simple application.

## Task 1 of 6
Step 1

`yum install -y git`{{execute}}

## Task 2 of 6
Step 2

`mkdir /tmp/sample`{{execute}}
## Task 3 of 6
Step 3

`cd /tmp/sample`{{execute}}

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

`cp ~/src/catalog/helloworld/deliverables/bdcatalog-centos7-bluedata-helloworld-3.0.bin`{{execute}}

`chgrep apache /srv/bluedata/catalog/<bundle>.bin`{{execute}}

`chmod ug+rx /srv/bluedata/catalog/<bundle>.bin`{{execute}}

Congrats!
