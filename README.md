[kuma.hyeon.me](http://kuma.hyeon.me)
========

```shell
sudo ln -s "$PWD/kuma.hyeon.me" /usr/share/nginx/welcome
```
```Nginx
# nginx config
server {
  listen 80 default_server;
  server_name _;
  root /usr/share/nginx/welcome;
}
```
