# Hadolint for Gitlab CI docker image

Gitlab CI is currently unable to work without `/bin/sh` being present in the docker image.

## Build
By default this uses the `latest` tag of `hadolint/hadolint`. Setting `BASE` allows to use a different tag.
