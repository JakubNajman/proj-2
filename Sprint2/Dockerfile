From ubuntu

RUN apt-get -y update && apt-get -y install \
    iperf3 \
    sudo \
    lsof \
    htop

EXPOSE 8089/tcp
//jezeli nie znajdziemy opcji z przypisaniem portu bedziemy musieli robic na defaultowym 5201

CMD iperf3 -s –p 8089
