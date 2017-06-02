# ansible-mediaserver
Automating setup of NAS with Plex capability

This is my Ansible playbook for my current NAS/plexmediaserver setup.

Based largely on the work of [Alex](https://github.com/IronicBadger/)

Currently, it covers the setup of the following - these will be marked once completed.

- [X] Base install - setting up volumes
- [X] SnapRaid for backup
- [X] NFS
- [X] SABnzbd
- [X] Sonarr
- [X] CouchPotato
- [ ] Plex Mediaserver
- [ ] CrashPlan backup


## Running the playbook

  ansible-playbook -i hosts webserver.yml