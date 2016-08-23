FROM elasticsearch:2.3.5
MAINTAINER Hidetoshi Imai <hidepin@gmail.com>

RUN gosu elasticsearch plugin install analysis-kuromoji && \
    gosu elasticsearch plugin install mobz/elasticsearch-head && \
    gosu elasticsearch plugin install license && \
    gosu elasticsearch plugin install marvel-agent

CMD ["elasticsearch"]