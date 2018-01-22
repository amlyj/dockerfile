FROM tomoncle/alpine
# author
MAINTAINER tom liyuanjunmail@qq.com
USER root
# file
COPY bin/consul /usr/local/bin/consul
ADD consul /etc/consul
# port
EXPOSE 8300 8500 8600
# command
ENTRYPOINT ["consul"]
CMD ["agent", "-config-file=/etc/consul/consul.json"]
