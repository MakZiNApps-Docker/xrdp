FROM makzin/xrdp:base

#Install Desktop Environment
RUN export DEBIAN_FRONTEND=noninteractive && \
    apt update && \
    apt install -y gnome-core && \
    rm -rf /var/lib/apt/lists/*
