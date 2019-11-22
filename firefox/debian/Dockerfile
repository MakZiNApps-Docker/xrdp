FROM makzin/xrdp:openbox

#Install Desktop Environment
RUN export DEBIAN_FRONTEND=noninteractive && \
    apt update && \
    apt install -y firefox-esr && \
    rm -rf /var/lib/apt/lists/*

RUN echo "firefox &" >> /etc/xdg/openbox/autostart