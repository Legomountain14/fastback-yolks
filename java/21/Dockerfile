FROM ghcr.io/pterodactyl/yolks:java_21

USER root

RUN groupmod -g 997 container \
    && usermod -u 997 container

USER container