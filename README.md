# Matrix Ansible all-in-one
[![Matrix Channel](https://img.shields.io/matrix/matrix-ansible-aio:entropia.de?server_fqdn=matrix.org)](https://matrix.to/#/#matrix-ansible-aio:entropia.de)
# Nothing to see here yet, just some discussions/planning

## Target audience
 - people setting up a server for their peergroup with limited sysadmin knowledge
 - sysadmins that don't want to think about the stuff much

## Goals
Deploy:
 - synapse
 - riot
 - bridges:
   - telegram
   - discord
   - whatsapp
   - ???
 - matrix-ircd
 - mjolnir
 - matrix-media-repo
 - coturn
 - web dashboards (need to be built first):
   - invite links for registration available for existing users
   - very basic admin panel

## Tech Stack
 - Ansible for config management and deployment
 - Containers (Docker first, Podman later)
 - Traefik for TLS and reverse proxying

## Documentation
 - mdbook
