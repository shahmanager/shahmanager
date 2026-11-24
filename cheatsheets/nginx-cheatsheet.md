# Nginx Reverse Proxy Configuration

Upstream routing block:
```nginx
upstream backend {
    server 127.0.0.1:8000;
    keepalive 32;
}
```


## Practical Idioms and Recipes

Security headers and SSL termination:
- `add_header Strict-Transport-Security 'max-age=31536000; includeSubDomains' always;`
- `proxy_set_header X-Forwarded-For $proxy_add_x_forwarded_for;`
