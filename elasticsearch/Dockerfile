FROM elasticsearch:5.0.0
MAINTAINER Hidetoshi Imai <hidepin@gmail.com>

RUN elasticsearch-plugin install x-pack && \
    elasticsearch-plugin install analysis-kuromoji

RUN echo 'xpack.security.enabled: false' >> config/elasticsearch.yml && \
    echo 'xpack.graph.enabled: false' >> config/elasticsearch.yml && \
    echo 'xpack.watcher.enabled: false' >> config/elasticsearch.yml

CMD ["elasticsearch"]
