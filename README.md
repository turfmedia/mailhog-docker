# mailhog-docker
MailHog in a tiny Docker image powered by Alpine Linux

# How to use this image

Print help:

```bash
docker run --rm turfmedia/mailhog --help
```
Run MailHog:

```bash
docker run -d --name=mailhog \
  -p 1025:1025 \
  -p 1080:1080 \
  turfmedia/mailhog
```
Access to Web UI using your browser:

```bash
open http://localhost:1080
```
