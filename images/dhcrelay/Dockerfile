FROM ubuntu:20.04

RUN apt update && apt install -y isc-dhcp-relay iproute2

ENTRYPOINT [ "/usr/sbin/dhcrelay" ]
CMD [ "--help" ]