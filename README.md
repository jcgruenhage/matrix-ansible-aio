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
   - [Telegram](https://telegram.org/) with https://github.com/tulir/mautrix-telegram
   - [Discord](https://discord.com/) with https://github.com/matrix-discord/mx-puppet-discord (requires breaking ToS for DMs)
   - [WhatsApp](https://www.whatsapp.com/) with https://github.com/tulir/mautrix-whatsapp
   - [Instagram DMs](https://www.instagram.com/) with https://github.com/Sorunome/mx-puppet-instagram
   - [Facebook Messenger](https://www.messenger.com/) with https://github.com/tulir/mautrix-facebook
   - [Steam DMs](https://store.steampowered.com/) with https://github.com/icewind1991/mx-puppet-steam
   - [TwitterDMs](https://twitter.com/) with https://github.com/Sorunome/mx-puppet-twitter (requires API Token from twitter)
   - [Skype](https://www.skype.com/) with https://github.com/Sorunome/mx-puppet-skype
   - [Slack](https://slack.com/) with https://github.com/Sorunome/mx-puppet-slack
   - [Mattermost](https://mattermost.com/) with https://github.com/matrix-hacks
/matrix-puppet-mattermost
   - [iMessage](https://support.apple.com/explore/messages) with https://github.com/matrix-hacks/matrix-puppet-imessage
   - [Signal](https://www.signal.org/) with https://github.com/witchent/matrix-puppet-signal
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

## Bikeshedding Topics
 - ansible galaxy vs git submodules
