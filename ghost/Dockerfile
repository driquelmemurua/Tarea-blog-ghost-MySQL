FROM ghost:1.20.0
RUN apt-get update -y && \
    apt-get install -y mysql-client
COPY ./bdd-config.sh /usr/local/bin/bdd-config.sh
