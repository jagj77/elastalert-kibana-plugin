FROM docker.elastic.co/kibana/kibana:7.13.4

COPY ./plugins/elastalertKibanaPlugin-7.13.4.zip plugins/
RUN ./bin/kibana-plugin install file:////usr/share/kibana/plugins/elastalertKibanaPlugin-7.16.2.zip
