FROM ubuntu:20.04

ENV DEBIAN_FRONTEND=noninteractive

RUN apt-get update \
    # Installing key components for running xv6
    && apt-get install -y gdb qemu-system-x86 build-essential gcc-multilib libc6-i386 \
    # Feel free to install w/e else you need
    # Clean up
    && apt-get autoremove -y && apt-get clean -y && rm -rf /var/lib/apt/lists/*

ENTRYPOINT ["bash"]
