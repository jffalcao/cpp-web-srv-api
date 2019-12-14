FROM gcc:7.3.0

RUN apt-get -qq update && \
    apt-get -qq upgrade && \
    apt-get -qq install cmake libboost-all-dev=1.62.0.1 build-essential libtcmalloc-minimal4 && \
    ln -s /usr/lib/libctmalloc_minimal.so.4 /usr/lib/libctmalloc_minimal.so

EXPOSE 8080

CMD [ "bash" ]

