FROM fedora:latest

RUN dnf update -y
RUN dnf install tar 
RUN curl https://storage.googleapis.com/flutter_infra_release/releases/stable/linux/flutter_linux_3.3.10-stable.tar.xz
RUN ls
RUN tar xf flutter_linux_3.3.10-stable.tar.xz


ENV PATH /flutter/bin/:$PATH