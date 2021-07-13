# fluentd/Dockerfile

FROM fluent/fluentd:v1.12.0-debian-1.0
USER root
RUN ["gem", "install", "fluent-plugin-elasticsearch", "--no-document", "--version", "5.0.3"]
USER fluent
COPY sample.log /tmp/sample.log
COPY KPI_Log.NRB /tmp/KPI_Log.NRB
