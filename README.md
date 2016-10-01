[![](https://images.microbadger.com/badges/image/teampiggycoin/piggyelectrum-server.svg)](https://microbadger.com/images/teampiggycoin/piggyelectrum-server "Get your own image badge on microbadger.com")

This is a trusted build on the [DockerHub repository](https://hub.docker.com/r/teampiggycoin/piggyelectrum-server/).

To run:

docker run -d -v /home/electrum/:/home/electrum -p 5001:5001 -p 5002:5002 -p 8000:8000 --name piggyelectrum-server teampiggycoin/piggyelectrum-server

Notes:

This connects by default to the dockerized teampiggycoin/piggycoind container if running on the same host (host-named piggycoind)
