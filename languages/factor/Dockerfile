#syntax=docker/dockerfile-upstream:1.4.0-rc1
FROM attemptthisonline/base

ARG FACTOR_VERSION=0.98

RUN curl -L https://downloads.factorcode.org/releases/$FACTOR_VERSION/factor-linux-x86-64-$FACTOR_VERSION.tar.gz | \
    tar -xz && \
    mv factor /opt/
