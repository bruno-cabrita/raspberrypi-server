# Hetzner DDNS

## Documentation
- [filiparag/hetzner_ddns Docker Hub](https://hub.docker.com/r/filiparag/hetzner_ddns)
- [filiparag/hetzner_ddns GitHub](https://github.com/filiparag/hetzner_ddns)
- [Hetzner DNS API](https://dns.hetzner.com/api-docs)

## Instructions
1. Go to [Hetzner DNS Console](https://dns.hetzner.com/)
2. Click on the pretended Zone
3. Add a `A` record with the `Name` of your subdomain (ex.`vpn`) and a bogus IP in the `Value` (ex:`1.1.1.1`)
4. Create a [Hetzner API Access Token](https://dns.hetzner.com/settings/api-token)
5. Make a copy the `conf` file with the command: `cp hetzner_ddns.conf.example hetzner_ddns.conf`
6. Edit the `hetzner_ddns.conf` file with your info
7. Start the container with: `docker compose up -d`