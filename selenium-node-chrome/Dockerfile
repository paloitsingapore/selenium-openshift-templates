FROM selenium/node-chrome:3.141.59-neon

ENV HOME=/home/seluser

USER root

COPY ./contrib /usr/local/bin

RUN chown -R 1001:0 /opt/selenium

USER 1001
WORKDIR $HOME
