FROM debian:buster-slim

#Install supervisor & xrdp
RUN export DEBIAN_FRONTEND=noninteractive && \
    apt-get update && \
    apt-get install -y supervisor xrdp && \
    rm -rf /var/lib/apt/lists/*

COPY xrdp.conf /etc/supervisor/conf.d/
COPY xrdp-sesman.conf /etc/supervisor/conf.d/

EXPOSE 3389

CMD ["supervisord", "--nodaemon", "-c", "/etc/supervisor/supervisord.conf"]