When adding docker and portainer:

If docker newer than 29 then:
```echo '{"min-api-version": "1.24"}' | sudo tee /etc/docker/daemon.json
systemctl restart docker


```
