FROM debian:jessie
MAINTAINER Guillaume Lhermenier <guillaume.lhermenier@gmail.com>

RUN apt-get update && apt-get install -y texlive-full

RUN mkdir /var/sources

WORKDIR /var/sources

CMD xelatex
