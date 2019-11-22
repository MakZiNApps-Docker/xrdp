FROM makzin/xrdp:base

#Install Desktop Environment
RUN export DEBIAN_FRONTEND=noninteractive && \
    apt update && \
    apt install -y openbox python && \
    rm -rf /var/lib/apt/lists/*
