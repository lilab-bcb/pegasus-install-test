FROM debian:buster-slim

RUN mkdir -p /usr/share/man/man1 && \
    apt update && \
    apt install -y build-essential python3 python3-pip default-jdk

RUN python3 -m pip install --upgrade pip && \
    python3 -m pip install pegasuspy && \
    python3 -m pip install leidenalg

RUN apt install -y libfftw3-dev && \
    python3 -m pip install fitsne