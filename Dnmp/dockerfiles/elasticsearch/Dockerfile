ARG ELASTICSEARCH_VERSION
FROM elasticsearch:${ELASTICSEARCH_VERSION}
ARG ELASTICSEARCH_VERSION
RUN cd /usr/share/elasticsearch && ./bin/elasticsearch-plugin install https://github.com/medcl/elasticsearch-analysis-ik/releases/download/v$ELASTICSEARCH_VERSION/elasticsearch-analysis-ik-$ELASTICSEARCH_VERSION.zip
