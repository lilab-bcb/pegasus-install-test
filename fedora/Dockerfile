FROM fedora:33

RUN dnf install -y gcc gcc-c++ python3.8 java-latest-openjdk fftw-devel && \
    python3.8 -m ensurepip --user

RUN pip3 install pegasuspy fitsne leidenalg