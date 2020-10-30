# Ceenter Ansible runner images

Set of image/s used for Ansible Tower Container Groups.

## Create container image

Login to Quay.io:

- Go to [quay.io robot accounts](https://quay.io/user/ceenter?tab=robots),
- login as Red Hat user *ceenter*,
- download login credentials.

Build and push container image:
``` shell
podman build -t quay.io/ceenter/ansible-runner-google:1.4.6 ./ansible-runner-google/
podman push quay.io/ceenter/ansible-runner-google:1.4.6
```
