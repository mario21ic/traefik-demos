Run
```
docker-compose up
```

Test
```
curl -H "Host: nginx.mario21ic.com" localhost/traefik/?foo=bar
curl -H "Host: web.mario21ic.com" localhost
curl -H "Host: apache.mario21ic.com" localhost/traefik?foo=bar
```

Dashboard:
Open http://localhost:8080/dashboard in your browser

http://apache.mario21ic.com/
http://web.mario21ic.com/
http://nginx.mario21ic.com/traefik/?foo=bar -> This doesn't need a new index.html