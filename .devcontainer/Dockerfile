
FROM rockylinux:9

RUN dnf -y update && \
    dnf -y install \
    git \
    curl \
    wget \
    vim \
    nano \
    sudo \
    python3 \
    python3-pip \
    procps-ng \
    iproute \
    iputils \
    tar \
    gzip \
    unzip \
    which \
    findutils \
    shadow-utils \
    && dnf clean all

ENV SHELL=/bin/bash

CMD ["/bin/bash"]
