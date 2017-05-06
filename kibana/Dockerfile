FROM kibana:5.4.0

RUN apt-get update

ENV ELASTICSEARCH_ENDPOINT http://elasticsearch:9200

ENTRYPOINT ["/bin/bash", "-c", "kibana --elasticsearch $ELASTICSEARCH_ENDPOINT"]
