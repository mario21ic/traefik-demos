Set up vms:
```
vagrant up
vagrant ssh apache -- -t "ip -4 addr show dev eth1"
vagrant ssh nginx -- -t "ip -4 addr show dev eth1"
```

docker-compose up

sudo vim /etc/hosts
127.0.0.1 nginx.mario21ic.com
127.0.0.1 httpd.mario21ic.com
127.0.0.1 web.mario21ic.com
127.0.0.1 server.nginx.mario21ic.com
127.0.0.1 server.apache.mario21ic.com

