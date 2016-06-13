[kuma.hyeon.me](https://kuma.hyeon.me)
========

```shell
sudo mv ./kuma.hyeon.me/ /usr/share/nginx/welcome
```
```Nginx
# nginx config
server {
  listen 80 default_server;
  server_name _;
  root /usr/share/nginx/welcome;
}
```

### HTTPS
[![](http://i.imgur.com/blwHEzZ.png)](https://www.ssllabs.com/ssltest/analyze.html?d=kuma.hyeon.me)
