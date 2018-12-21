# Docker based on the latest CentOS 7 image - non-privileged user entry
FROM centos:latest
MAINTAINER victor.vedmich@gmail.com

RUN useradd -ms /bin/bash user

ENTRYPOINT echo "This command will display this message on EVERY container"

USER user
