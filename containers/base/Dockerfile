FROM ubuntu:16.04

RUN apt-get update
RUN apt-get install -y git build-essential cmake libboost-all-dev

RUN git clone https://github.com/pluracoin/PluraCoin.git

RUN cd PluraCoin && make
