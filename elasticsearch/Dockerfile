FROM elasticsearch:5.0.0
MAINTAINER Hidetoshi Imai <hidepin@gmail.com>

RUN elasticsearch-plugin install x-pack && \
    elasticsearch-plugin install analysis-kuromoji

CMD ["elasticsearch"]
