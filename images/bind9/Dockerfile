FROM ubuntu:20.04

RUN apt update && apt install -y bind9 iproute2

ENTRYPOINT [ "/usr/sbin/named" ]
CMD [ "--help" ]