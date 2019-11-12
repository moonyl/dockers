FROM darkmattercoder/qt-build:builder-5.12.5

RUN apt-get update && \
    apt-get -y dist-upgrade && \
    apt-get -y install cmake && \
    apt-get -qq clean && \
    rm -rf /var/lib/apt/lists/*