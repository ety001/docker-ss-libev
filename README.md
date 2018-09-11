# Shadowsocks-libev for Docker

[![Docker pulls][pulls-image]][hub-url]
[![Docker stars][stars-image]][hub-url]
[![Docker size][size-image]][size-url]

A mini docker image of [Shadowsocks-libev](https://github.com/shadowsocks/shadowsocks-libev) only 15M in size.

## Tags

- `2.4.6`
- ...
- `2.5.6`
- `3.0.7`
- `3.0.8`, `latest`

## Usage

```
$ docker pull ety001/ss
$ docker run -d -p the_port_you_configed:the_port_you_configed -v your_config:/conf/shadowsocks.json --restart=always --name ss ety001/ss
```
