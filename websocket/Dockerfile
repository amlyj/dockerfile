#version 1.0
FROM kingaric/alpine

MAINTAINER aric liyuanjunmail@sian.com

USER root

ADD websocket /opt/websocket

WORKDIR /opt/

RUN echo http://nl.alpinelinux.org/alpine/v3.1/main >/etc/apk/repositories  &&\
    apk update && apk add python

EXPOSE 30001 30011

VOLUME ["/data","/storage/data"]

CMD  python /opt/websocket/server.py
