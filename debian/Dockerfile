FROM debian:stretch-slim

RUN apt-get update && \
    apt-get install -y \
                    autoconf \
                    automake \
                    bc \
                    bison \
                    build-essential \
                    curl \
                    dpkg-dev \
                    fakeroot \
                    file \
                    flex \
                    gawk \
                    git \
                    libgmp-dev \
                    libmpc-dev \
                    libmpfr-dev \
                    libtool \
                    linux-headers-4.9.0-4-amd64 \
                    texinfo \
                    wget && \
rm -rf /var/lib/apt/lists/*

# Add user and set entrypoint
RUN useradd -m -U -s /bin/sh -u 1234 user
