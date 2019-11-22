FROM makzin/xrdp:base

#Install Desktop Environment
RUN export DEBIAN_FRONTEND=noninteractive && \
    apt update && \
    apt install -y xfce4 xfce4-goodies && \
    rm -rf /var/lib/apt/lists/*
