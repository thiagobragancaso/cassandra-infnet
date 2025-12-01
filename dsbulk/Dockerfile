FROM eclipse-temurin:17-jre
LABEL authors="thiagobso"
RUN wget -q -P /opt -O /opt/dsbulk.tar.gz https://github.com/datastax/dsbulk/releases/download/1.11.0/dsbulk-1.11.0.tar.gz
RUN tar -xzf /opt/dsbulk.tar.gz -C /opt && rm /opt/dsbulk.tar.gz
ENV PATH="/opt/dsbulk-1.11.0/bin:${PATH}"