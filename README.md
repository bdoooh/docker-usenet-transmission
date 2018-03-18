# Usenet / Transmission Docker

## Containers
* [haugene/docker-transmission-openvpn](https://github.com/haugene/docker-transmission-openvpn) - Transmission
  * Inlcuded in this is support for VPN Unlimited which isn't provided out of the box at the above repo

## Docker Setup
1. Copy environment-variables to a .env file & fill in the data 
```
cp environment-variables .env
```
2. Run `docker-compose up -d`
