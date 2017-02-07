FROM kibana:4.5.1

RUN gosu kibana kibana plugin --install elasticsearch/marvel
RUN gosu kibana kibana plugin --install elastic/sense

EXPOSE 9200 5601
