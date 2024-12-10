```
go generate && go build && sudo ./firewall
```

- [ ] Go 언어에서 [객체 로딩하기](https://ebpf-go.dev/concepts/loader/)
- [ ] Redis에서 CIDR, IP 가져와서 처리
- [ ] 임계치 기반 차단 구현

## in arm64
```shell
apt install linux-headers-`uname -r`
ln -s /usr/include/aarch64-linux-gnu/asm /usr/include/asm
ifconfig enp0s6 mtu 2000 
```
