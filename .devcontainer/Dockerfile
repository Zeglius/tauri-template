FROM mcr.microsoft.com/devcontainers/rust:1-1-bookworm

RUN apt update -y && \
    apt install -y \
        libwebkit2gtk-4.1-dev \
        build-essential \
        curl \
        wget \
        file \
        libssl-dev \
        libayatana-appindicator3-dev \
        librsvg2-dev \
    && apt clean -y