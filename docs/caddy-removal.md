# Caddy Replacement

Caddy disabled in Tutor configuration.

## Config Changes
```yaml
ENABLE_WEB_PROXY: false
ENABLE_HTTPS: false
```

## Replacement
Nginx Ingress Controller handles all traffic.

## Verification
Check kubernetes/tutor-config.yml
