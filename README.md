## Description
docker-image helps you build docker images 😉, without having to create a Dockerfile.

It currently supports node applications and expects the deployable files to be in ./dist.

## Installation

```bash
npm i @olaleyeone/docker-image -D
```

## Usage

### Without arguments

```bash
$ npx docker-image
```

### With tag

```bash
$ npx docker-image -t my-image
```

### With base image and tag

```bash
$ npx docker-image --from node:14.10.1-alpine3.12 -t my-image
```
