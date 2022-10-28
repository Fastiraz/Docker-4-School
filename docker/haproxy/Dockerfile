FROM ubuntu

RUN apt update -y
RUN apt upgrade -y
RUN apt install -y haproxy
COPY haproxy.cfg /etc/haproxy/