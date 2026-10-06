# farihas-firewall

A reverse-proxy Web Application Firewall (WAF), built from scratch.

## What it does

- Inspects HTTP requests for common attack patterns: SQL injection, XSS, path traversal, command injection
- Rate-limits and flags anomalous behavior (e.g. brute-force attempts)
- Logs every decision in structured JSON
- Visualizes blocked attacks on a simple dashboard

## Status

Work in progress.

## Testing

Validated against intentionally vulnerable apps (OWASP Juice Shop / DVWA) running in Docker.
