ARG ELK_VERSION

# https://www.docker.elastic.co/
FROM docker.elastic.co/kibana/kibana:${ELK_VERSION}

# Add your kibana plugins setup here
# Example: RUN kibana-plugin install <name|url>

# https://opendistro.github.io/for-elasticsearch-docs/docs/install/plugins/
# https://opendistro.github.io/for-elasticsearch-docs/docs/install/docker/
# COPY ./opendistroAlertingKibana-1.13.0.0.zip /tmp/
# RUN bin/kibana-plugin install file:///tmp/opendistroAlertingKibana-1.13.0.0.zip
RUN kibana-plugin install https://github.com/opendistro-for-elasticsearch/alerting-kibana-plugin/releases/download/v1.13.0.0/opendistroAlertingKibana-1.13.0.0.zip