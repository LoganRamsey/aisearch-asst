FROM mcr.microsoft.com/devcontainers/base:ubuntu

# Install dependencies
RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get install -y \
        curl \
        apt-transport-https \
        ca-certificates \
        gnupg \
        lsb-release \
        software-properties-common \
    && rm -rf /var/lib/apt/lists/*

# Make scripts folder
RUN mkdir -p /scripts
