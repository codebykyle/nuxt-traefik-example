# Nuxt Traefik Test

A stack example

Generate keys

```bash
echo "AUTHENTIK_SECRET_KEY=$(openssl rand -base64 60 | tr -d '\n')" >> .env
```