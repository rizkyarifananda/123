### Command Install

```
rm -f setup.sh && sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://raw.githubusercontent.com/rizkyarifananda/123/main/setup.sh && chmod +x setup.sh && ./setup.sh
```

This Script is Good For:

1. SSH + OVPN
2. SSHWS + SSLWS
3. VMESS & VLESS
4. L2TP & PPTP

Notes:
1. Fail2Ban is - ON
2. Dflate is - ON
3. IPTables is - ON
4. Auto Reboot is - ON
