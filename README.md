#Docker

```sh
Add the EPEL Repository

rpm -iUvh http://dl.fedoraproject.org/pub/epel/6/x86_64/epel-release-6-8.noarch.rpm

UpdatePackage

yum update -y

Installation

yum -y install docker-io

start Docker Deamon

service docker start

Start docker on boot

chkconfig docker on

Download a Docker Container

docker serach centos docker pull centos

Run a Docker Container

docker run -i -t centos /bin/bash
```
