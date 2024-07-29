# Use the official Apache ActiveMQ Artemis image as the base
FROM apache/activemq-artemis:2.35.0

COPY docker-run.sh /docker-run.sh

USER root
RUN chmod +x /docker-run.sh

RUN mkdir -p /opt/artemis/data/
RUN chmod 777 /opt/artemis/data/

USER artemis
EXPOSE 61616 8161



