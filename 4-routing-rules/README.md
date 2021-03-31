Run
```
docker-compose up
```

Test
```
curl -H "Host: nginx.mario21ic.com" localhost
curl -H "Host: web.mario21ic.com" localhost
curl -H "Host: apache.mario21ic.com" localhost/traefik?foo=bar
```

Dashboard:
Open http://localhost:8080/dashboard in your browser
