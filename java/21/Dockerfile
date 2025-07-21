FROM ghcr.io/pterodactyl/yolks:java_21

USER root

RUN groupmod -g 986 container \
    && usermod -u 999 container

USER container