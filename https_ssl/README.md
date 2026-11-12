DNS subdomains and HTTPS for my web stack (clovistek.tech).

- `1-haproxy_ssl_termination`: HAProxy config from lb-01 that accepts HTTPS on port 443 (SSL termination)
- `2-redirect_http_to_https`: HAProxy config that also redirects HTTP to HTTPS (301)
