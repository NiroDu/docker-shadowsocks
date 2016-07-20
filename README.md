docker-shadowsocks
==================
[![Build Status](http://drone.xueqingxiao.tech/api/badges/xueqingxiao/docker-shadowsocks/status.svg)](http://drone.xueqingxiao.tech/xueqingxiao/docker-shadowsocks)

Usage
-----

```shell
$ docker run -d -p 1984:1984 oddrationale/docker-shadowsocks -s 0.0.0.0 -p 1984 -k password -m aes-256-cfb
```

For more command line options, refer to the [shadowsocks documentation](https://github.com/shadowsocks/shadowsocks)