FROM mcr.microsoft.com/devcontainers/base:ubuntu

RUN apt-get update && \
    apt-get install -y \
        gcc \
        git \
        make \
        qemu-system-x86 \
    && rm -rf /var/lib/apt/lists/*
