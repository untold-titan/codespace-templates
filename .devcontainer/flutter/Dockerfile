FROM fedora:latest

RUN dnf update -y
RUN dnf install tar xz git which -y
RUN curl -o flutter.tar.xz https://storage.googleapis.com/flutter_infra_release/releases/stable/linux/flutter_linux_3.3.10-stable.tar.xz
RUN tar xf flutter.tar.xz
RUN git config --global --add safe.directory /flutter
# Installing MS Edge for web development
RUN curl -o edge-browser.rpm https://packages.microsoft.com/yumrepos/edge/microsoft-edge-stable-109.0.1518.61-1.x86_64.rpm?brand=M102
RUN dnf install -y edge-browser.rpm


ENV PATH /flutter/bin/:$PATH
ENV CHROME_EXECUTABLE /opt/microsoft/msedge/microsoft-edge