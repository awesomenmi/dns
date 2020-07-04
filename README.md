# DNS/DHCP - настройка и обслуживание 

```vagrant up```

``vagrant ssh client1/client2``

Проверка DNS-resolution:

```
dig web1.dns.lab
dig web2.dns.lab
dig www.newdns.lab
dig -x 192.168.50.25/192.168.60.15

dig @192.168.50.11 web1.dns.lab
dig @192.168.50.11 web2.dns.lab
dig @192.168.50.11 www.newdns.lab
dig @192.168.50.11 -x 192.168.50.25/192.168.50.15
```
