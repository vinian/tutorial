# iptables

##


## usefule commands

capture first two packets of tcp conversation
```shell
tcpdump -nni any port 22 and tcp[13] == 2
```
