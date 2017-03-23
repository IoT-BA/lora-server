## LoRa Server
Docker image of [loraserver](https://github.com/brocaar/loraserver). LoRa Server is an open-source LoRaWAN network-server.
All configurable parameters are set through enviroment variables in docker-compose.yml, more info can be found in [loraserver docs](https://docs.loraserver.io/loraserver/)

### Build image
    sudo docker build -t iotba/lora-server .
