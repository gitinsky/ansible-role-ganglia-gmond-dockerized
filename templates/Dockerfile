FROM gitinsky/baseimage:0.1.4
MAINTAINER Git In Sky <support@gitinsky.com>

RUN \
  apt-get update && \
  apt-get -y install ganglia-monitor && mkdir /etc/service/gmond

ADD ./run /etc/service/gmond/run

EXPOSE 80
