### TCP BBR v2 Alpha

---

Compile time : 16/1/2020

Support : Debian 10 (Buster)

```
echo "net.core.default_qdisc = fq" >> /etc/sysctl.conf
echo "net.ipv4.tcp_congestion_control = bbr2" >> /etc/sysctl.conf
echo "net.ipv4.tcp_ecn = 1" >> /etc/sysctl.conf
echo "net.ipv4.tcp_ecn_fallback = 1" >> /etc/sysctl.conf
sysctl -p
```

Sources : [google/bbr](https://github.com/google/bbr.git)
