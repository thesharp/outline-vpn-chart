# Outline VPN Helm Chart

## How to install

```bash
helm repo add outline https://thesharp.github.io/outline-vpn-chart/
helm repo update

helm upgrade --install outline . -n outline --create-namespace --atomic
```
