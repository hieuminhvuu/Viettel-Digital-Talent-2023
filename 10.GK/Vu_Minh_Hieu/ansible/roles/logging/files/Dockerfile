FROM fluent/fluentd:v1.16.1-debian-arm64-1.0
USER root
RUN ["gem", "install", "elasticsearch", "--no-document", "--version", "8.7.1"]
RUN ["gem", "install", "fluent-plugin-elasticsearch","--no-document","--version", "5.3.0"]
USER fluent