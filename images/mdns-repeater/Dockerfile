FROM ubuntu:20.04

RUN apt-get update && apt-get install -y \
    build-essential \
    git-core

WORKDIR /tmp
RUN git clone https://github.com/kennylevinsen/mdns-repeater.git

WORKDIR /tmp/mdns-repeater
RUN make && mv mdns-repeater /usr/bin/

ENTRYPOINT ["/usr/bin/mdns-repeater"]
CMD ["-h"]
