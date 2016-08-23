FROM kibana:4.5.4
MAINTAINER Hidetoshi Imai <hidepin@gmail.com>

RUN gosu kibana kibana plugin --install elasticsearch/marvel/latest

CMD ["kibana"]