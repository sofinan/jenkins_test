FROM ubuntu:latest
RUN apt update && apt install curl wget busybox-extras netcat-openbsd python py-pip -y
RUN pip install awscli
CMD tail -f /dev/null
