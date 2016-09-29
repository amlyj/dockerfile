FROM kingaric/centos:7
RUN mkdir -p /tmp/redis && \
    cd /tmp/redis && \
    curl -ssl -O https://raw.githubusercontent.com/king-aric/librarys/master/redis/redis-3.2.3.bin.tar && \
    tar xvf redis-3.2.3.bin.tar -C /opt && \
 
CMD [ "/opt/redis/bin/redis-server","--protected-mode no","/opt/redis/redis.conf" ]
