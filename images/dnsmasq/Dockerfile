FROM ubuntu:20.04

RUN apt update && apt install -y dnsmasq iproute2

ENTRYPOINT [ "/usr/sbin/dnsmasq" ]
CMD [ "--help" ]