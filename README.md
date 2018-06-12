# Hadolint for Gitlab CI docker image

Gitlab CI is currently unable to work without `/bin/sh` being present in the docker image.
This docker image provides a solution by using `alpine` as a slim base and copies `/bin/hadolint` on top of that.

## Build
By default this uses the `latest` tag of `hadolint/hadolint`. Setting `BASE` allows to use a different tag.
