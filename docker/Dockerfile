FROM debian:stretch
LABEL maintainer="greenrenovatedbonds Developers <dev@greenrenovatedbonds.org>"
LABEL description="Dockerised greenrenovatedbondsCore, built from Travis"

RUN apt-get update && apt-get -y upgrade && apt-get clean && rm -fr /var/cache/apt/*

COPY bin/* /usr/bin/
