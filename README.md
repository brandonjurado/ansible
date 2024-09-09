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

- `TAILSCALE_AUTHKEY` - Ephemeral authentication key for Tailscale using a `ci` tag that has SSH configured in your ACL

_TODO: Use OAuth instead of Authkey for Tailscale_