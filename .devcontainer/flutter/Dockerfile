FROM ubuntu

RUN apt-get update
RUN apt-get install -y curl git unzip snapd
RUN systemctl start snapd
RUN systemctl status snapd
RUN snap install flutter --classic
RUN flutter doctor