# iptables

##


## usefule commands

capture first two packets of tcp conversation
```shell
tcpdump -nni any port 22 and tcp[13] == 2
```

or
```shell
tcpdump -i any -nn -s 0 "tcp[tcpflags] & (tcp-syn) != 0"
```
