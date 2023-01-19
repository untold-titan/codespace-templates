FROM fedora:latest

# RUN dnf update -y
RUN curl -o flutter.tar https://storage.googleapis.com/flutter_infra_release/releases/stable/linux/flutter_linux_3.3.10-stable.tar.xz
RUN ls
RUN tar -xf /flutter.tar 
RUN ls


ENV PATH /flutter/bin/:$PATH