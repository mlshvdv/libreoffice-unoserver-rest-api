# libreoffice-unoserver with REST API

The LibreOffice with unoserver on Docker

## About

This uses the [`alpine:3.16`](https://hub.docker.com/_/alpine) as base images.

**NOTE**: Please fork or create a new project from this template to build your own image.

### Pre-built image

We do not provide stable pre-built images, but we have an unstable `nightly` image for testing.

```
libreofficedocker/libreoffice-unoserver:nightly
```

### REST API

This image shipped with REST API for unoserver by default.

How to use: https://github.com/libreoffice-docker/unoserver-rest-api.

### Environment Variables

| Variable      | Default   | Required | Description               |
| ------------- | --------- | -------- | ------------------------- |
| UNOSERVER_CMD | unoserver |          | Set the unoserver command |

## License

Licensed under [Apache-2.0 license](LICENSE)
