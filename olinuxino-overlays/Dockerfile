FROM debian:sid

ENV DEBIAN_FRONTEND noninteractive

# Install packages
RUN apt-get update && apt-get install -y --no-install-recommends \
	bats build-essential debhelper-compat device-tree-compiler devscripts git git-buildpackage \
&& rm -rf /var/lib/apt/lists/*
