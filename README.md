# Ansible

### Dependencies:

Required on the host machine:
- `Tailscale`
  - `ci` tag is configured in `Tailscale` with SSH access
- `git`
  - must have authentication to Github for ssh
- `ansible`
  - ansible-vault secrets: [ `webhook_url` ]

#### Secrets

- `TAILSCALE_OAUTH_ID`
- `TAILSCALE_OAUTH_SECRET`