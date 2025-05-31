FROM postgres:17.5

RUN apt-get update && \
    apt-get install patroni -y --no-install-recommends && \
    mkdir -p /etc/patroni/ &&\
    apt-get clean && rm -rf /var/lib/apt/lists/*
