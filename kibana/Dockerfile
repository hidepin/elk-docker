FROM kibana:5.0.0
MAINTAINER Hidetoshi Imai <hidepin@gmail.com>

RUN kibana-plugin install x-pack && \
    kibana-plugin install timelion

CMD ["kibana"]
