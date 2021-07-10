# SecUp - Docker Image Security Updater

## Idea
1. specify a base Image to update Packages
2. specify base OS (debian, alpine etc.)
3. App generates Dockerfile depending base OS with update command ("apt-get upgrade", "apk update" etc.)
4. App builds new Image with base Image tag or custom tag and pushes into registry

## Needed Information
- BaseImage
- credentials, if private registry
- OS of baseImage

## Configuration
- viper and yaml file?

## SKDs, APIs etc.
- [docker Engine API](https://docs.docker.com/engine/api/v1.41/#operation/ImageList)


## Supported Engines
- docker

### Maybe in future?
- kaniko
- buildah

