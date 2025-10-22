# Home server
 
A collection of applications running on a home server

# Services

## Syncthing

- [Syncthing docker image](https://docs.linuxserver.io/images/docker-syncthing/)
1. After the container is running, log in at <http://ip_address:8384>

## Immich

- Immich docs: https://docs.immich.app/

1. After the container is running, log in at <http://ip_address:2283>
1. You will be prompted to create an admin account
1. Click the user icon (Username initial at top right)
1. Select `Administration > External Libraries > Create Library`
1. Set import path to `/files/media` and save
1. Select `Scan` and any photos in the drive will be uploaded to Immich
