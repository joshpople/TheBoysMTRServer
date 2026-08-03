# TheBoysMTRServer Resource Pack Merge and Upload.

This repo is for my Minecraft server to allow Resource Packs to be merged and downloaded by clients joining

## Deployment secrets

The GitHub Action deploys using these repository secrets:

1. `SERVER_HOST` - hostname or IP of the new server
2. `SERVER_USER` - SSH user on that server
3. `SERVER_SSH_KEY` - private key for that user

The manifest URL is now generated from `SERVER_HOST` as:

`http://<SERVER_HOST>`