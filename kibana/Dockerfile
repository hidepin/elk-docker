FROM kibana:5.0.0
MAINTAINER Hidetoshi Imai <hidepin@gmail.com>

RUN kibana-plugin install x-pack && \
    kibana-plugin install timelion && \
    chown -R kibana:kibana /usr/share/kibana

RUN echo 'xpack.security.enabled: false' >> /etc/kibana/kibana.yml && \
    echo 'xpack.graph.enabled: false' >> /etc/kibana/kibana.yml && \
    echo 'xpack.reporting.enabled: false' >> /etc/kibana/kibana.yml

CMD ["kibana"]
