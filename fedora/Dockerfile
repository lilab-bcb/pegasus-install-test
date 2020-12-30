FROM fedora:33

RUN dnf install -y gcc gcc-c++ python3.8 java-latest-openjdk && \
    python3.8 -m ensurepip --user && \
    python3.8 -m pip install --upgrade pip

RUN python3.8 -m pip install pegasuspy

RUN dnf install -y fftw-devel && \
    python3.8 -m pip install fitsne leidenalg
