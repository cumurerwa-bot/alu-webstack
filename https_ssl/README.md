# HTTPS SSL

- `0-world_wide_web`: displays the DNS record type and destination of
  subdomains (www, lb-01, web-01, web-02) of a given domain.
- `1-haproxy_ssl_termination`: HAProxy config terminating SSL on port 443.
- `2-redirect_http_to_https`: HAProxy config redirecting HTTP to HTTPS (301).
