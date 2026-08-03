# Vaultwarden

Open source password management solution, based on
[Vaultwarden][vaultwarden].

This app is published as a prebuilt image (`ghcr.io/cchrkk/app-vaultwarden`)
and is kept up to date automatically: a GitHub Action checks for a new
Vaultwarden release every 6 hours and publishes an updated version.

## Configuration

- **ssl**: Enables HTTPS (default: `true`).
- **certfile / keyfile**: Paths to the SSL certificate and key in `/ssl`.
- **request_size_limit**: Optional limit for the web vault.

[vaultwarden]: https://github.com/dani-garcia/vaultwarden
