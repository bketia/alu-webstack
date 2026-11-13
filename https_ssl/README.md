# HTTPS SSL

| File | Description |
| ---- | ----------- |
| `0-world_wide_web` | Displays the DNS record type and destination of a domain's subdomains. |
| `1-haproxy_ssl_termination` | HAProxy config terminating SSL on port 443 for www.bezastudio.tech. |
| `2-redirect_http_to_https` | HAProxy config that also redirects HTTP to HTTPS with a 301. |
