FROM debian:testing

ENV DEBIAN_FRONTEND noninteractive

# Install packages
RUN apt-get update && apt-get install -y --no-install-recommends \
	bc bison build-essential device-tree-compiler flex gcc-aarch64-linux-gnu gcc-arm-linux-gnueabihf libfdt-dev libpython3-dev python3 python3-distutils swig quilt \
	debhelper-compat devscripts git git-buildpackage gnupg2 \
	libc6-dev-arm64-cross libc6-dev-armhf-cross \
&& rm -rf /var/lib/apt/lists/*
