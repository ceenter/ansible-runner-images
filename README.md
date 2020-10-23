# Ceenter Ansible runner images

Set of image/s used for Ansible Tower Container Groups.

## Build image

``` shell
podman build -t quay.io/jveverka/ansible-runner-google:1.4.6 ./google-auth/
podman push quay.io/jveverka/ansible-runner-google:1.4.6
```
