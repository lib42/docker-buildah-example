# Docker Image Build - Using Buildah

This is an example on how to build container images using buildah & Gitlab-CI.

## Requirements

For this example to work you will need some additional environment variables inside of your Gitlab-Project:

| Variable | Meaning | Example |
|:--------:|:-------:|:-------:|
| REGISTRY      | Registry prefix for the image | docker.io    |
| REGISTRY_USER | Username of Registry-Account  | nold360      |
| REGISTRY_PASS | Password of Registry-Account  | ************ |

## Configuration
For the configuration of the Gitlab-CI Job see `.gitlab-ci.yml`.
