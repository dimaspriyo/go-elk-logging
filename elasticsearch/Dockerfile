FROM docker.elastic.co/elasticsearch/elasticsearch:7.7.0
RUN sysctl -w vm.max_map_count=262144
RUN /usr/share/elasticsearch/bin/elasticsearch -Des.logger.level=DEBUG