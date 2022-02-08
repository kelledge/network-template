FROM ubuntu:20.04

RUN apt update && apt install -y isc-dhcp-server iproute2

ENTRYPOINT [ "/usr/sbin/dhcpd" ]
CMD [ "--help" ]