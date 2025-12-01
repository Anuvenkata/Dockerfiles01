ARG VERSION
FROM almalinux:${VERSION:-9}
ARG COURSE="DOCKER" \
    TRAINER="SIVA"  
ENV COURSE=${COURSE}
RUN echo "Trainer: ${TRAINER}, Course: ${COURSE}, version: ${VERSION}"
CMD ["sleep" , "1000"]


# docker build -t arg.v1 --build-arg VERSION=8 --build-arg COURSE=AWS .

#[ ec2-user@ip-172-31-68-170 ~/Dockerfiles01/ARG ]$ docker run -d arg.v1:latest
#321dc82cf002ff0676c9830a2c7a5e531a9a175c7695098c0ce696395882c093


#[ ec2-user@ip-172-31-68-170 ~/Dockerfiles01/ARG ]$ docker exec -it 32 /bin/bash
#[root@321dc82cf002 /]# env
#LANG=C.utf8
#HOSTNAME=321dc82cf002
#COURSE=AWS
#PWD=/
#HOME=/root
#TERM=xterm
#SHLVL=1
#3PATH=/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
#LESSOPEN=||/usr/bin/lesspipe.sh %s
#_=/usr/bin/env
#[root@321dc82cf002 /]#
