docker-shadowsocks
==================
[![Build Status](http://drone.xueqingxiao.tech/api/badges/xueqingxiao/docker-shadowsocks/status.svg)](http://drone.xueqingxiao.tech/xueqingxiao/docker-shadowsocks)

Usage
-----

```shell
$ docker pull xueqingxiao/docker-shadowsocks
$ docker run --name=shadowsocks --restart=always -p 8388:8388 -d xueqingxiao/docker-shadowsocks -s 0.0.0.0 -p 8388 -k password -m aes-256-cfb
```

For more command line options, refer to the [shadowsocks documentation](https://github.com/shadowsocks/shadowsocks/tree/master)