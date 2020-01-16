### TCP BBR v2 Alpha

---

Compile time : 16/1/2020

Sources : [google/bbr](https://github.com/google/bbr.git)

```
net.core.default_qdisc = fq
net.ipv4.tcp_congestion_control = bbr2
net.ipv4.tcp_ecn = 1
net.ipv4.tcp_ecn_fallback = 1
```
