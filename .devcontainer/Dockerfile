FROM mcr.microsoft.com/vscode/devcontainers/base:0-ubuntu-22.04

USER root
RUN apt-get update

USER vscode

RUN mkdir /home/vscode/opt && cd /home/vscode/opt && git clone https://github.com/flutter/flutter.git -b stable

ENV PATH $PATH:/home/vscode/opt/flutter/bin
