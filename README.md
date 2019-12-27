
# V2ray Config examples

This repository contains various configuration examples for [V2ray](https://www.v2ray.com/).

## Naming topology

The configuration names are following the below convention to represent the topology of the v2ray nodes inbound setup and how the configuration is going to work:

`[ Client ] - [ Bridge ] - [ Upstream ]`

For example `socks5-vmess-vmess` tells us that the client accepts socks5 connection and connects to the bridge with `vmess` protocol and then bridge also connects to the upstream with `vmess` protocol.

## Examples

- [socks5-vmess-vmess](socks5-vmess-vmess)
