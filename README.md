# AwsCli Dockerfile

# Base Docker Image

* [alpine:3.6]

# Installation

1. Install [Docker](https://www.docker.com/)

2. Get automated build from public registry: `docker pull sijokg/awscli`


# Usage

Use image to run container

```
docker run -it --rm sijokg/awscli
```

Provide AWS access credentials as environment variables

```
docker run -it --rm \
--env AWS_ACCESS_KEY_ID=access_key \
--env AWS_SECRET_ACCESS_KEY=secret_key \
denvazh/awscli-docker
```
