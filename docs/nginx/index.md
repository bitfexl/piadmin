[Install Nginx Webserver](https://bitfexl.github.io/piadmin/nginx)

# Nginx Webserver

> [nginx](https://nginx.org/en/) [engine x] is an HTTP and reverse proxy server, a mail proxy server, and a generic TCP/UDP proxy server

**Basic HTTP server features**

> -   Serving static and [index](https://nginx.org/en/docs/http/ngx_http_index_module.html) files
> -   [Reverse proxying with caching](https://nginx.org/en/docs/http/ngx_http_proxy_module.html), [load balancing](https://nginx.org/en/docs/http/ngx_http_upstream_module.html)
> -   Filters include [gzipping](https://nginx.org/en/docs/http/ngx_http_gzip_module.html)
> -   [SSL and TLS SNI support](https://nginx.org/en/docs/http/ngx_http_ssl_module.html)

**For short:**
Nginx is a Webserver which can serve static files (html files, images, css files, js files, ...) and it can do that via https (as any website should do). It can also act as an [reverse proxy](https://en.wikipedia.org/wiki/Reverse_proxy) distributing requests between different webservers.

## Install

```bash
sudo apt update -y
sudo apt install nginx -y
```

Typing the ip address of the Raspberry into the address bar of your browser should now display something like this:

![Welcome to nginx!](welcomeToNginx.png | width=300)
