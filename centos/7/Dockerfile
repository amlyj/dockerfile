#version 7

FROM centos:7
MAINTAINER aric king-aric@sina.com
RUN for lib in wget vim ; do  if rpm -ql $lib ; then echo $lib ; else yum -y install $lib ; fi done
VOLUME ["/datavolume","/volumestorage"]
CMD /bin/bash
