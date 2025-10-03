![CI](https://github.com/akadilou/hardlock/actions/workflows/ci.yml/badge.svg)
![Deploy](https://github.com/akadilou/hardlock/actions/workflows/deploy.yml/badge.svg)

# Hardlock – Produit (V1)

Hardlock = appli mobile sécurisée.
Hardlock Guard (Platform) = service backend (KMS + API + Proxy).

## Architecture
App (iOS/Android) → HTTP(S) → API (attest_api) → KMS.

## Environnements
Dev local : http://127.0.0.1:8088/api/...
Staging : https://staging.hardlock.app/api/...
Prod : https://api.hardlock.app/...

## Roadmap courte
V1: 3 endpoints stables (/health, /pubkey, /attest), stack locale.
V2: déploiement cloud (TLS), SDK iOS/Android, observabilité.
