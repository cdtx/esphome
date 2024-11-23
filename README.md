docker pull ghcr.io/esphome/esphome:2024.11  
esphome='docker run --rm -it --privileged -v "${PWD}":/config --device=/dev/ttyUSB0 --net=host ghcr.io/esphome/esphome:2024.11 '  

esphome run <yaml>
