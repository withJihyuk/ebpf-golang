```
go generate && go build && sudo ./firewall

```

## in arm64
```shell
apt install linux-headers-`uname -r`
ln -s /usr/include/aarch64-linux-gnu/asm /usr/include/asm
ifconfig enp0s6 mtu 2000 
```
